---
chunk_index: 3809
ref: "2d09a2165a01"
id: "2d09a2165a01bf1acebfc3e0379ef5c745e64862bc651be1fd06ab662690815f"
slug: "chunk-168--writing-note-the-user-s-view-of-scrolling"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_168.md"
kind: "markdown"
lines: [3, 12]
token_estimate: 509
content_sha256: "e3b472979be714d2407695876ef42d45b50f14a79ad498bb35a8a5127c689ec5"
compacted: false
heading_path: ["**Writing Note: The User's View of Scrolling**"]
symbol: null
address: null
asset_path: null
---

#### **Writing Note: The User's View of Scrolling**  
By *moving* the knob in the bar, users metaphorically *move* an opening around on the surface of a document so that they can see the portions they desire. Visually, of course, it's the document that appears to *move,* not the opening. This means that the knob and the display *move* in opposite directions. To avoid confusion, the user interface and the application's documentation should concentrate on the metaphor of adjusting the portion of the document that's visible, rather than adjusting the document to make it visible.  
The scroll buttons for both vertical and horizontal scrollers should occupy the lower left comer, where the two scrollers meet. Keeping all the scroll buttons in the same region makes it easy for users to move from one set to the other.  
Controls that determine how a scrollable document is viewed can be placed within the area normally occupied by the scrollers (beneath and to the left of the document). Other sorts of controls should not be placed within this area.  
![](images/_page_163_Figure_2.jpeg)  
Among the controls that can be placed in the scroller area are these:  
- An editable text field to display the current page number can be located to the far right of the horizontal scroller (as shown above).
- A pop-up list that lets the user scale the display can be located in the area of the horizontal scroller (as shown above).
- A pop-up list used to control the viewing mode for the display (for example, preview versus drawing mode in a graphics application) can be similarly situated to the zoom pop-up list in the area of the vertical scroller.
- Page scroll buttons that scroll from page to page or by viewfuls can be grouped next to the line scroll buttons in the lower left comer where the vertical and horizontal scrollers meet. Since there is no Application Kit support for page scroll buttons, but there might be in the future, a precise arrangement is not currently specified. (Typical page scroll buttons are shown above.)