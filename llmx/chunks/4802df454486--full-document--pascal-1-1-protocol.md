---
chunk_index: 183
ref: "4802df454486"
id: "4802df4544861cbd91aadd83215198d2f7bc3b430b04d701d95fae48e67843da"
slug: "full-document--pascal-1-1-protocol"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [195, 255]
token_estimate: 1117
content_sha256: "0b0cd00d4094223a76f53098dc8735c7170f80cc7f7b91d39b30068353ed41b5"
compacted: false
heading_path: ["Peripheral Card Firmware","Pascal 1.1 Protocol"]
symbol: null
address: null
asset_path: null
---

## Pascal 1.1 Protocol

Pascal 1.1 has a more flexible setup and supports more input/output functions than BASIC or Pascal 1.0. It makes indirect calls to the firmware in a (new) peripheral card through addresses in a branch table in the card's firmware. It also has facilities for uniquely identifying new peripheral I/O devices.

The I/O routine entry point branch table is located near the beginning of the \$cs00 address space (s being the slot number where the peripheral card is installed). This space was chosen instead of the \$c800 space, since under BASIC protocol the \$cs00 space is required, while the \$c800 space is optional.

The branch table locations that Pascal 1.1 uses are:

| Address    | Contains                                         |
|------------|--------------------------------------------------|
| \$ C s O D | initialization routine offset (required)         |
| \$ C s O E | read routine offset (required)                   |
| #Cs0F      | write routine offset (required)                  |
| \$ C s 1 0 | status routine offset (required)                 |
| \$Cs11     | \$00 if optional offsets follow; non-zero if not |
| \$Cs12     | control routine offset (optional)                |
| \$Cs13     | interrupt handling routine offset (optional)     |

Notice that \$cs11 contains \$00 only if the control and interrupt handling routines are supported by the firmware. Apple II Pascal 1.0 and 1.1 do not support control and interrupt requests, but such requests may be implemented in future versions of the Pascal BIOS and other future Apple II operating systems.

Here are the entry point addresses, and the contents of the 6502 registers on entry to and on exit from Pascal 1.1 I/O routines:

| Addr.      | Offset for                            | X Register           | Y Register          | A Register                                |
|------------|---------------------------------------|----------------------|---------------------|-------------------------------------------|
| \$CsOD     | Initialization<br>On entry<br>On exit | \$Cs<br>error code   | \$s0<br>(unchanged) | (unchanged)                               |
| \$ C s O E | Read<br>On entry<br>On exit           | \$Cs<br>error code   | \$s0<br>(unchanged) | character read                            |
| \$Cs0F     | Write<br>On entry<br>On exit          | \$Cs<br>error code   | \$s0<br>(unchanged) | char. to write (unchanged)                |
|            | Status<br>On entry<br>On exit         | \$ C s<br>error code | \$s0<br>(changed)   | \$0s10<br>request (0 or 1)<br>(unchanged) |

**Notes:** Request code 0 means, "Are you ready to accept output?" Request code 1 means, "Do you have input ready?" On exit, the reply to the status request is in the carry bit: carry clear means "No"; carry set means "Yes."

Pascal 1.1 uses four firmware bytes to identify the peripheral card. Both the identifying bytes and the branch table are near the beginning of the \$cs00 ROM space. The identifiers are listed in the following table.

| Address | Value                                      |
|---------|--------------------------------------------|
| \$Cs05  | \$38 (standard BASIC requirement)          |
| \$Cs07  | \$18 (standard BASIC requirement)          |
| \$Cs0B  | \$01 (generic signature of firmware cards) |
| \$Cs0C  | \$ci (device signature; see below)         |

The first digit, c, of the device signature byte identifies the device class.

| Digit | Class                               |
|-------|-------------------------------------|
| \$0   | reserved                            |
| \$1   | printer                             |
| \$2   | joystick or other X-Y input device  |
| \$3   | serial or parallel I/O card         |
| \$4   | modem                               |
| \$5   | sound or speech device              |
| \$6   | clock                               |
| \$7   | mass storage device                 |
| \$8   | 80-column card                      |
| \$9   | network or bus interface            |
| \$A   | special purpose (none of the above) |
| \$B-F | reserved for future expansion       |

The second digit, i, of the device signature byte is a unique identifier for the card, assigned by Apple Technical Support. For example, the Apple Ile 80-Column Text Card has a device signature of \$88.

Although version 1.1 of Pascal ignores the device signature, applications programs can use them to identify specific devices.