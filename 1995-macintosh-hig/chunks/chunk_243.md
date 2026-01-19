<!-- Chunk 243 | Source: 1995 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 417 -->
The Clear key has the same effect as the Clear command in the Edit menu; that is, it removes the selection from the document without putting it in the Clipboard. Because not all Macintosh keyboards have Clear keys, no application should ever *require* use of the Clear key.  
![](images/_page_300_Picture_12.jpeg)  
#### Escape 10  
The Escape (Esc) key has the general meaning "let me out of here." It's a sort of panic button for the user. In certain contexts its meaning is specific:  
- The user can press Escape as an alternate to clicking the Cancel button in a dialog box.
- The user can press Escape to stop an operation in progress, such as printing. Using the Escape key in this way has the same effect as using the keyboard equivalent Command-period.  
The Keyboard **277**  
<span id="page-301-0"></span>If an application absolutely requires a series of dialog boxes, the user should be able to use Escape to move backward through the boxes. However, you should avoid getting into this situation for the reasons described in Chapter 6, "Dialog Boxes," in the section "Stacking Modal Dialog Boxes" on page 192.  
Pressing Escape should never cause the user to back out of an operation that would require extensive time or work to reenter. Also, pressing Escape should never cause the user to lose valuable information. When the user presses Escape during a lengthy operation, the application should display a confirmation dialog box to be sure that Escape wasn't pressed accidentally. An example of a message you might post is shown in Figure 10-10.  
**Figure 10-10** A sample confirmation dialog box for the Escape key  
![](images/_page_301_Figure_5.jpeg)