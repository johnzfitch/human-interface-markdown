---
chunk_index: 2984
ref: "5e209b2705a4"
id: "5e209b2705a4facae2a4f5e86db8e8893744141b55ab14864b07dc94b148b0ea"
slug: "full-document--dialog-boxes"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [5929, 5965]
token_estimate: 1129
content_sha256: "3e4aeeaf867e484a30c772ab05d38e5ac68047b95e7747fd24711551e7e6ccfa"
compacted: false
heading_path: ["Dialog Boxes"]
symbol: null
address: null
asset_path: null
---

# Dialog Boxes

- Are questions in dialog boxes posed in a straightforward and positive way–for example, "Do you want to erase everything on the disk named "James Bond?" rather than "Do you not want to alter the contents of this disk?"
- Do dialog boxes and alert boxes appear on the screen where the user's focus of attention is, not necessarily where the menu bar is?
- Are dialog boxes horizontally centered either on the screen or over the active window if the window is on a large screen or on a screen other than the one the menu bar appears on?
- If a movable modal dialog box is displayed, can the application run in the background?
- Do you provide access to the menu bar when you display a movable modal dialog box? Are the Help, Edit, Keyboard, and Application menus enabled as appropriate?
- Are movable modal dialog boxes truly modal within the application?
- Do movable modal dialog boxes have a drag region (title bar)? Do movable modal dialog boxes not have a close box? For black-and-white monitors, do movable modal dialog boxes have a two-pixel-wide outline within the content region to signify that it is a modal dialog box?
- Can the Help menu be used when a modal dialog box is displayed?
- If there is an active editable text box in a modal dialog box, can the Cut, Copy, Paste, and Undo menu commands in the Edit menu be used?
- Do keyboard equivalents of the standard Edit menu commands operate correctly in a modal dialog box containing editable text items?
- When a scrolling list is present in a dialog box, can type selection be used? Can the arrow keys be used to move the selection by one item in the direction of the arrow?
- Does the active area of a dialog box have an indicator if there is more than one possible active area? (Active areas are those that accept typing such as scrolling lists with type selection or text boxes.)

Dialog Boxes **355**

- Does clicking a desired element move the active area to that element?
- Does pressing the Tab key cycle through the available elements? Does Shift-Tab cycle in the reverse direction?
- When appropriate, are buttons named with a verb that describes the action that it performs, such as Erase rather than OK?
- Do you provide a Cancel button wherever possible, especially in progress dialog boxes? Does pressing Escape or Command-period indicate Cancel in a dialog box or alert box? (Pressing Escape should never cause the user to lose information.)
- If an operation can be halted midstream, with possible side effects, is the button named Stop instead of Cancel?
- Do the Return and Enter keys map to the default button, which is usually the button with the safest result or the most likely response?
- Are default buttons outlined with an additional border of three black pixels, separated by a border of one white pixel?
- Do you avoid displaying a default border around any button when you use the Return key in editable text boxes?
- When a button is activated by keyboard equivalents, is the button highlighted for eight ticks of the clock to give visual feedback that the item has been chosen?
- Are buttons 20 pixels high? Are they wide enough for their text names (with a minimum of 8 pixels on each side of the text)?
- Are buttons placed in functional and consistent locations, both within your application and across all applications that you develop? Is the action button placed in the lower-right corner with the Cancel button to its left or above (for Western readers)?
- Do you use a consistent amount of white space between the border of the dialog box and its elements, thus creating a balanced appearance in the dialog box?
- When a dialog box or alert box refers to a document or an application, do you use the name of the document or application in the text?
- Do you use curly quotation marks (single and double) instead of straight quotation marks? (This also applies to apostrophes.)
- When you must unavoidably nest dialog boxes, do you dim the background dialog box and buttons, so that the frontmost dialog box stands out?
- Do your modeless dialog boxes have a close box? Such dialog boxes should not have buttons that dismiss the dialog box.
- Has room been left to allow the dialog box to grow during localization? Most languages require more characters than English to convey equivalent messages.

Are display rectangles of dialog box items (for example, radio buttons and checkboxes) the same size? When the alignment of dialog box items is reversed, the items should align on the opposite side.