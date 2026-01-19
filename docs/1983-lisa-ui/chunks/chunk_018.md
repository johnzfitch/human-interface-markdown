<!-- Chunk 18 | Source: 1983 Lisa UI Guidelines.pdf | Est. Tokens: 273 -->
The user deactivates a window by clicking outside of it. When she does this, the document stays just as it is; the application does not ask her to finish doing anything. When the user reactivates the window, the application picks up where it left off.  
A descrivated <del>Lisawriter</del> document is shown in Figure 9.  
5-2  
Source: David T Craig  
![](images/_page_12_Figure_1.jpeg)  
Floure 9. Deactivated LisaCalc Document  
Details: When the user deactivates a window, the display changes in the following ways:  
- 1) The scroll ber portion of the window is shown in white.
- 2) The title bar is no longer highlighted.
- If a selection is visible in the window, it is highlighted with a gray pattern rather then in inverse video.
- 4) The menus for the application disappear from the menu bar.  
Implementation: Automatic in the Toolkit. The Toolkit provides a gray pattern for dinhighlingting, but the application can use its own pattern if it wents. Alternatively, it can nake the dinhighlighting look like a regular selection or like a deselection if necessary for sesthetic reasons.