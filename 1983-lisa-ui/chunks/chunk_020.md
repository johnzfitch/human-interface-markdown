<!-- Chunk 20 | Source: 1983 Lisa UI Guidelines.pdf | Est. Tokens: 178 -->
Save & Continue saves all changes to the document without closing its window. The appearance of the window, including the current position and selection, remain unchanged.  
Some applications, such as LisaList, save documents at times other than when the user has explicitly saved them from the File/Print menu. If it is necessary for an application to do this, it should warn the user that this is happening.  
#### Details:  
Implementation: By default, an active document has two files associated with it: The Save file, written to only when the document is saved, and the Suspend file, which contains the document heap and which is swapped out from time to time. Saving the document deletes the Suspend file.