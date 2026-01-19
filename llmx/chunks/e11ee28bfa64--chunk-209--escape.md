---
chunk_index: 2434
ref: "e11ee28bfa64"
id: "e11ee28bfa643a1fbfab4b43677db24c2b5bdcd5c58cead63f70ad08aa000037"
slug: "chunk-209--escape"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_209.md"
kind: "markdown"
lines: [21, 29]
token_estimate: 331
content_sha256: "d8d9d04b048755c182f58c131ea2d41d64ee55e816c7c12497ed9c4ce54f62ee"
compacted: false
heading_path: ["Enter","Tab","Return","Escape"]
symbol: null
address: null
asset_path: null
---

#### Escape  
The Escape (Esc) key has the general meaning "let me out of here." It's a sort of panic button for the user. In certain contexts its meaning is specific:  
- The user can press Escape as an alternate to clicking the Cancel button in a dialog box.
- The user can press Escape to stop an operation in progress, such as printing. Using the Escape key in this way has the same effect as using the keyboard equivalent Command-period.  
The Keyboard **277**  
If an application absolutely requires a series of dialog boxes, the user should be able to use Escape to move backward through the boxes. However, you should avoid getting into this situation for the reasons described in Chapter 6, "Dialog Boxes," in the section "Stacking Modal Dialog Boxes" on page 192.  
Pressing Escape should never cause the user to back out of an operation that would require extensive time or work to reenter. Also, pressing Escape should never cause the user to lose valuable information. When the user presses Escape during a lengthy operation, the application should display a confirmation dialog box to be sure that Escape wasn't pressed accidentally. An example of a message you might post is shown in Figure 10-10.  
**Figure 10-10** A sample confirmation dialog box for the Escape key  
![](images/_page_301_Figure_5.jpeg)