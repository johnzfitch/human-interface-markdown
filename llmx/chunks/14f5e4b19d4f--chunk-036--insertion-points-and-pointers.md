---
chunk_index: 695
ref: "14f5e4b19d4f"
id: "14f5e4b19d4fd1702924d225c9ee8815be579c38e13f2f8e10e4b0309b019ec9"
slug: "chunk-036--insertion-points-and-pointers"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_036.md"
kind: "markdown"
lines: [7, 20]
token_estimate: 644
content_sha256: "6868a9ee2c8f16c2bff5c998234588d4f9ada614ce72fe6a361485a8d4d1726e"
compacted: false
heading_path: ["Insertion Points and Pointers"]
symbol: null
address: null
asset_path: null
---

#### Insertion Points and Pointers  
Each pointer has a **hot spot**, the portion of the pointer that must be positioned over a screen object before mouse clicks can have an effect on that object. The hot spot should be intuitive, such as the tip of an arrow pointer or the center point of a crosshair pointer. Mouse clicks have effect only when the pointer's hot spot is positioned over the target object's **hot zone**.  
Don't confuse the user by changing the pointer's shape without a reason. You might want to have the pointer change shape to give feedback on the range of activities that make sense either in a particular area of the screen or in a current mode. Sometimes, the result of mouse actions depends on the item under the pointer when the mouse button is pressed. Where an application uses modes for different functions, the pointer can be a different shape in each mode. For example, in MacPaint, the pointer shape always reflects the currently selected tool.  
Figure 3 shows some examples of pointers and their effect. An application can use additional pointers as needed for other contexts.  
| <u>Pointer</u> | <u>Name</u>           | Used for                                                                         |
|----------------|-----------------------|----------------------------------------------------------------------------------|
|                | Arrow                 | Scroll bar and other controls, size box, title bar, menu bar, desktop, and so on |
| Ţ              | l-beam                | Selecting and inserting text                                                     |
| +              | Crosshairs            | Drawing, shrinking, or stretching graphic objects                                |
| ₹}-            | Plus Sign             | Selecting fields in an array                                                     |
| 4              | Wristwatch            | Showing that a lengthy operation is in progress                                  |
|                | Spinning<br>Beachball | Showing that the system is still alive during a lengthy operation                |  
Figure 3. Pointers  
During a particularly lengthy operation, when the user can do nothing but wait until the operation is completed, the pointer may change its shape and become a status or progress indicator. This indicator lets the user know that the system hasn't died—it's just busy. The standard pointer used for this purpose is a wristwatch. During even longer operations, the beachball pointer spins to provide positive feedback that all is well.