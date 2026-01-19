---
chunk_index: 2350
ref: "c1ec2163ba58"
id: "c1ec2163ba58926baf4658e654988694475607c7246b0100b82fc6e7bb809a4b"
slug: "chunk-136--stacking-modal-dialog-boxes"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_136.md"
kind: "markdown"
lines: [10, 15]
token_estimate: 564
content_sha256: "f861b7a33854a483fcb74ee07ba2810b338897b65137024a20eee7f513f2d51e"
compacted: false
heading_path: ["Menu Bar Access","Stacking Modal Dialog Boxes"]
symbol: null
address: null
asset_path: null
---

#### Stacking Modal Dialog Boxes  
Ideally a user should see only one modal dialog box at a time. The user should never see more than two modal dialog boxes on the screen at any time. One example where a second modal dialog box appears is when the user saves a file with the same name as another file. Then the Standard File Package displays an alert box on top of the standard file dialog box. The alert box questions the user about whether to replace the existing file. If the user answers the question by clicking the Replace button, the alert box and the standard file dialog box both disappear and the action is completed. If the user clicks the Cancel button, the alert box disappears and the standard file dialog box remains on the screen; this allows the user to perform another action, such as saving the file with a different name.  
If you find that you can't avoid displaying a second modal dialog box, make sure to obscure as little as possible of the first modal dialog box. Also make sure that the first dialog box (the one in the background) is dimmed when the second dialog box appears. (You dim the dialog box by dimming the border and buttons, and by unhighlighting any text selection; make sure your application stores the text selection so that it can restore it when the second dialog box is dismissed.) By dimming the dialog box in the background, you focus the attention of the user on the active dialog box—the one in which the user must click. Figure 6-16 shows two modal dialog boxes correctly displayed. Notice that the alert box appears on top of the dialog box for saving files, but doesn't totally obscure it. In this way, users still get some context for the current action.  
**Figure 6-16** Second modal dialog box on top of first one  
![](images/_page_216_Picture_3.jpeg)  
Avoid closing a modal dialog box and displaying another modal dialog box in response to a user action. This situation creates a "tunneling modal dialog box" syndrome from which it is difficult to recover. Since the previous modal dialog box is not there for context, the user can't predict what will happen next, and can't get back to the last place. In other words, don't create a situation where the user is caught in a maze of dialog boxes.