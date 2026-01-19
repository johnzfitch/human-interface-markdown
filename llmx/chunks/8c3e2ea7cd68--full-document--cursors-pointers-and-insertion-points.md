---
chunk_index: 1382
ref: "8c3e2ea7cd68"
id: "8c3e2ea7cd68446aa14f4e9cbf6012ec4569f914b203b5823c27e42f2b1c3043"
slug: "full-document--cursors-pointers-and-insertion-points"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1462, 1481]
token_estimate: 770
content_sha256: "00d5fb2c9c63163a7efcd400d2072e665641a162473a87350e7416eba1dea8fc"
compacted: false
heading_path: ["Cursors, pointers and insertion points"]
symbol: null
address: null
asset_path: null
---

# Cursors, pointers and insertion points

Traditional character-oriented command-line interfaces rely on a **cursor** to indicate the the place on the display where the next character that is typed will appear. The user uses arrow keys (sometimes called "cursor keys") to move the cursor around the screen. Because there is nothing else to "point" at, no pointer is needed.

In the desktop interface, on the other hand, there may be many graphical objects on the screen, unrelated to the text insertion point, to point at. The screen **pointer** is logically attached to the mouse or other pointing device; the user manipulates it to show the application what to do next, and where to do it. What Apple calls an **insertion point** shows where the next characters to be typed will appear. In text, the pointer shows where the insertion point will be moved to if the mouse button is pressed.

Each pointer has a **hot spot**—the portion of the pointer that must be positioned over a screen object before mouse clicks can have an effect on that object. The hot spot should be intuitive, such as the tip of an arrow pointer or the center point of a crosshair pointer. Mouse clicks have effect only when the pointer's hot spot is positioned over the target object's **hot zone**.

As the pointer moves about the screen, it may change shape. For example, in a text-oriented program the pointer takes the I-beam shape while it's within the text, to show where the insertion point will move to if the mouse button is pressed. When the pointer moves outside the text, it becomes an arrow. Don't confuse the user by changing the pointer's shape without a reason. You might want to have the pointer change shape to give feedback on the range of activities that make sense either in a particular area of the screen or in a current mode. Sometimes, the result of mouse actions depends on the item under the pointer when the mouse button is pressed. Where an application uses modes for different functions, the pointer can be a different shape in each mode. For example, in MacPaint, the pointer shape always reflects the currently selected tool.

Figure 48 shows some examples of pointers and their effects. An application can create additional pointers as needed for other contexts.

| <u>Pointer</u> | Name       | Used for                                                                         |
|----------------|------------|----------------------------------------------------------------------------------|
| R              | Arrow      | Scroll bar and other controls, size box, title bar, menu bar, desktop, and so on |
| I              | l-beam     | Selecting and inserting text                                                     |
| +              | Crosshair  | Drawing and modifying graphic objects                                            |
| 4              | Plus Sign  | Selecting fields in an array                                                     |
| <b>_</b>       | Wristwetch | Showing that a lengthy operation is in progress                                  |