---
chunk_index: 1972
ref: "49cd0be90fdb"
id: "49cd0be90fdb00a7bdaca8f8b31ffd709234d22c813b9a613cd0817950c0eb47"
slug: "full-document--open"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [1649, 1666]
token_estimate: 415
content_sha256: "1fce59b3d8a06fa59826922a1624bf5f56eea130808d1e36c9cd114444fdc65a"
compacted: false
heading_path: ["The Apple menu","The File menu","New","Open"]
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