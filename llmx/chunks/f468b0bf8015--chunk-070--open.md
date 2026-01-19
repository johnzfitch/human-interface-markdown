---
chunk_index: 1726
ref: "f468b0bf8015"
id: "f468b0bf80159f3f4e0190e29df63cd01c5d896025a3db7d2a24fb755bbb0459"
slug: "chunk-070--open"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/chunks/chunk_070.md"
kind: "markdown"
lines: [15, 23]
token_estimate: 417
content_sha256: "6652980b4c3eb5fd5857800d58ee99c001df3ae8803758bfca173ddc37849e26"
compacted: false
heading_path: ["The File menu","New","Open"]
symbol: null
address: null
asset_path: null
---

#### Open  
Opens an existing document. A dialog box lets the user select *which* document. This dialog box shows a list of all the documents on the disk whose name is displayed that can be handled by the current application (Figure 3-29 and Figure 3-30). Which dialog box appears depends on the file system on the disk. With the Macintosh File System (MFS), used on 400K disks, all the documents are displayed together in one list; folders are ignored.  
![](images/_page_89_Picture_4.jpeg)  
Figure 3-29 MFS Open dialog box  
With the Hierarchical File System (HFS) on the Macintosh, the user, when opening a document, can browse through all levels of folders, forward and backward. The Eject and Drive buttons allow the user to look at documents on another disk or to eject a disk. When no disk is available to look at or to eject, these buttons are dimmed.  
![](images/_page_89_Picture_7.jpeg)  
Figure 3-30 HFS Open dialog box  
Using Open from an application, the user can open only <sup>a</sup> document that can be processed by that application. To open a document that can be processed only by some other application, the user must ordinarily leave the application and return to the Finder. Using Open from the Finder, the user can open any document—the appropriate application is automatically opened as well.  
When an application starts up by putting an empty untitled document on the screen, the Open option can remain enabled (not dimmed) even ifthe application allows only one open document at <sup>a</sup> time. In this case, choosing Open from the File menu simultaneously closes the empty document (why save an empty document?) and opens another.