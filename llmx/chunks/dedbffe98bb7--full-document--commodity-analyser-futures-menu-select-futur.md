---
chunk_index: 237
ref: "dedbffe98bb7"
id: "dedbffe98bb7be3ecb1de435b74eb085eee53896b2a5469bce46314b3e2c4452"
slug: "full-document--commodity-analyser-futures-menu-select-futur"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [1043, 1068]
token_estimate: 663
content_sha256: "e232cc221c9425d6810dc4642a95217adf5d79419c1c52b88eadd885ad068fa8"
compacted: false
heading_path: ["**Displays**","Help","Menus","Commodity Analyser Futures Menu Select Future"]
symbol: null
address: null
asset_path: null
---

#### Commodity Analyser Futures Menu Select Future

- 1. Pork Belly Futures
- 2. Corn Futures
- 3. Present Futures
- 4. Crystal Ball Futures
- 5. Return to the Main Menu

Type your Selection (1-5) and press RETURN: \_...

Options: ESCAPE to leave OPEN-APPLE-? for help

The exact number of lines devoted to the three regions is not graven in stone: the real standard being striven for is that there be three regions with solid lines separating them, that these be devoted to titles, choices presented, and instructions. (The Apple II and Apple II Plus can not produce a solid line in text mode; use either their hyphens or their short-underline characters.

The title region can have up to three titles (usually two in forty-column mode). The middle title (or left title, if only 2) should be the name of the menu, and it should contain the word, "menu." Other displays you will use, such as data entry and information, may have a similar format: make sure your user is clearly aware of what he is being asked to do. Similarly, on information screens, do not number itemized lists, asterisk them: otherwise, about 25% of your users will try to type in a "selection".

You may use or not use the other titles as you see fit, but they should have a consistent meaning throughout a given application.

Note that a field length longer than one has been allowed for the number input. A field length of only one character will not give the user enough feedback as to how the input works. Users who have typed the wrong number will often panic, assuming the computer has somehow locked up. By giving them a few extra spaces, they can see from the action on the screen what is going on and deduce what to do about it. Since you will be stripping leading and trailing spaces (won't you?), this extra freedom afforded the user will not affect the program.

The instruction region doubles as the error message region.

One method you can use to enable the user to get descriptions of any option is to have them type the number of the option, followed by the help key (OPEN-APPLE-? on the Apple IIe and Apple III, ? on the Apple II and II Plus). The user is able to get extensive information only on those items of interest, without having to wade through masses of information that are not needed.

Routines for doing these menus will be available from Apple: first in Pascal for the Apple *III* in the Screen Manager and in BASIC for the Apple II series within the sample programs (Magic Menu, Disk Menu, etc.) supplied with the Apple IIe Applesoft Tutorial and Reference manuals package. The BASIC version is implemented with the help facility described above.