---
chunk_index: 2767
ref: "a40da2e77141"
id: "a40da2e77141ddebfbcdc78be79f7ef3fa87ac9ae946c18f0da28182af18afcf"
slug: "full-document--modeless-dialog-box-appearance"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2871, 2894]
token_estimate: 429
content_sha256: "c838930aae72b8b888f27bcc877884a615d58db7e969d75e8d23f4ed06713457"
compacted: false
heading_path: ["Modeless Dialog Boxes","Modeless Dialog Box Appearance"]
symbol: null
address: null
asset_path: null
---

## Modeless Dialog Box Appearance

Modeless dialog boxes look like basic document windows. A modeless dialog box has a title bar that displays its title, which should be the same as the name of the menu item that displays it. If that item includes an ellipsis character, *don't* include it in the title of the dialog box.

Figure 6-4 shows the appearance of a modeless dialog box.

**Figure 6-4** The essential elements of a modeless dialog box

![](images/_page_203_Figure_4.jpeg)

Modeless dialog boxes have the same behaviors as document windows—that is, the user manipulates them in the same way. For example, the user closes a modeless dialog box by using the close box or the Close command in the File menu. If you support keyboard equivalents for menus, support Command-W to close modeless dialog boxes as well as windows.

A modeless dialog box always has a close box; don't implement buttons to make the window disappear. The user expects that modeless dialog boxes stay on the screen until he or she explicitly dismisses them with the close box, *not* when he or she clicks a button in the dialog box.

Using a button to close a modeless dialog box also confuses the distinction between modeless dialog boxes and modal dialog boxes. Further, a modeless dialog box without a close box looks similar to a movable modal dialog box, thereby creating more confusion. Figure 6-5 shows a modeless dialog box that is missing its close box.

**Figure 6-5** Incorrect absence of a close box in a modeless dialog box

![](images/_page_204_Picture_3.jpeg)

If the user activates another window while a modeless dialog box is open, the window appears in front of the dialog box.

![](images/_page_204_Picture_5.jpeg)