<!-- Chunk 26 | Source: 1983 Lisa UI Guidelines.pdf | Est. Tokens: 323 -->
Revert to Previous Version restores a document to the way it was the last time it was saved. Usually, this means the last time the user explicitly saved it, but in some applications, such as LisaList, this can mean the last time the application saved it.  
If a document is not memory-resident, the application keeps changes to the document separate from the original version of the document, as described above (section 5.1). If the document is memory resident, the application keeps a separate, unchanged copy.  
Details: Suspend, deactivate, and set aside do not affect the contents of the current version. If the user reactivates the document and chooses Revert to Previous Version, the version he gets is the last one established by a save before the suspend, deactivate, or set aside.  
Implementation: Automatic in the Toolkit for LisaCalc-style applications. For LisaList-style applications, the Toolkit routines are assisted by application methods.  
![](images/_page_15_Picture_0.jpeg)  
![](images/_page_16_Picture_0.jpeg)  
![](images/_page_17_Figure_0.jpeg)  
![](images/_page_18_Figure_0.jpeg)  
![](images/_page_19_Figure_0.jpeg)  
![](images/_page_20_Figure_0.jpeg)  
![](images/_page_21_Figure_0.jpeg)  
![](images/_page_22_Figure_0.jpeg)  
![](images/_page_23_Figure_0.jpeg)