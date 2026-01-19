---
chunk_index: 512
ref: "62fdebf86917"
id: "62fdebf86917412a859af38bb3f14d10e3da3a0939b5f4a8ad0469789b7bcc1f"
slug: "full-document--marking-groups-of-selections"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [901, 952]
token_estimate: 1084
content_sha256: "e7170e4333beb113b7c6da28e3d1118f74c5cb67f47960580d3a7aec6edf73a3"
compacted: false
heading_path: ["Marking Groups of Selections:"]
symbol: null
address: null
asset_path: null
---

# Marking Groups of Selections:

Quite often, particularly in file-related functions and options, such as printer option screens, you have a group of names or options which the user needs to select or deselect, turn on or turn off.

[show with MouseText check-marks in place of -->'s]

Fred's Utilities Main Menu Copy a File

Escape: Exit to

| .d2/ FRED MODIFIED: | Na   | ame:        | TYPE:  | S   | IZE:   | DATE      |  |
|---------------------|------|-------------|--------|-----|--------|-----------|--|
|                     | Z    | ILLA.TEXT   | TEXT   | 1   | BLOCK  | 3-AUG-85  |  |
|                     | SI   | HAWN.TEXT   | TEXT   | 1 2 | BLOCKS | 4-AUG-85  |  |
|                     | HO   | OUSE.FOTO   | BINARY | 5   | BLOCKS | 29-JUL-82 |  |
|                     | L    | AZARUS      | SYS    | 1   | BLOCK  | 17-APR-85 |  |
|                     | SI   | HERI.FORMS  | TEXT   | 2   | BLOCKS | 6-AUG-85  |  |
|                     | > RI | UPERTS.LIST | TEXT   | 4   | BLOCKS | 3-JUL-85  |  |
|                     | RO   | ODS.NOTES   | TEXT   | 1   | BLOCK  | 12-JUN-85 |  |
|                     | JI   | DS.MISC.    | TEXT   | 14  | BLOCKS | 6-AUG-85  |  |
|                     | Al   | MY.MEMO     | TEXT   | 4   | BLOCKS | 14-JUL-86 |  |
|                     | TH   | HAD.MEMO    | TEXT   | 23  | BLOCKS | 18-JUL-85 |  |
|                     | > PI | ETER.MEMO   | TEXT   | 2   | BLOCKS | 3-AUG-85  |  |
|                     | L    | EE.MEMO.3   | TEXT   | 2   | BLOCKS | 3-AUG-85  |  |
|                     | LE   | EE.MEMO.4   | TEXT   | 1   | BLOCK  | 4-AUG-85  |  |

To Move: Press arrow keys To Mark/Unmark Documents: Press Solid-Apple To Accept Marked Documents: Press RETURN.

Help: OPEN-APPLE-?

[end of display]

If there is not enough room on the display for all names, scroll the display when the pointer (highlighting) reaches the bottom. When there are hidden file names, display a note at the bottom (or top, when files are hidden above) that says:

(Additional file names)

Because of the lack of special keys on the Apple II and Apple II Plus, there has never been a standard way of doing selections such as these. Use your imagination, and make the design you come up with conform to the rest of your program.

"Press Return to continue"

The user controls the movement from one display to the next by pressing

the Return key (or, optionally but consistently, Space bar). He is informed by a message such as, "Press the Return key to go on to the menu." on the bottom line of the screen. (Delay loops are difficult to judge as to the proper duration, and become somewhat insulting to the intelligence of the user.) The actual prompt message should give some indication as to what will happen next, rather than simply saying "Press Return to continue."

The educational software community has pretty much selected Space bar instead of Return to control movement: children were found to occasionally press Reset by accident on the older Apple II's and Apple II+'s. Please be consistent in your choice of Return key or Space bar, not only within a given program, but across your complete product line.

Do not tell the user to, "Press any key". On the Apple II series computers, you cannot currently read every key by itself: Reset, Shift, Control. We have also found in testing that new users panic when asked to press any key. Over 80% of them will turn around and say, "but what key should I press?" In questioning them about this response, we discovered that they are quite convinced that even though the prompt implied all keys were O.K. to press, some could be dangerous. Of course, they were usually quite right.

While you should not tell them to press any key, you may, in this specific case, accept more than the key specified. Both Return and Space bar can be accepted, even though only one is prompted for: users grow used to using one or the other. The exception to this lies in alert messages: use Space bar for dangerous, unusual alerts rather than Return. The habitual user will attempt to clear most alerts with scarcely a glance, but when Return fails to clear it, she or he will be forced to look further.

Never accept Escape instead of Return or Space bar, unless the latter two keys will result in the same thing the user would expect of Escape: moving up one level.