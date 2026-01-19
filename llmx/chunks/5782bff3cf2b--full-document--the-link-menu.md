---
chunk_index: 4136
ref: "5782bff3cf2b"
id: "5782bff3cf2b649c9af671bbf81b6519a46245209b3d74af18697f99a9898390"
slug: "full-document--the-link-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2354, 2373]
token_estimate: 766
content_sha256: "75aba8763b4d8eb49fd57ffab2c91cb05d4462fb28def9a3b6e12d30982136f8"
compacted: false
heading_path: ["5 *Panels*","**The Link Menu**"]
symbol: null
address: null
asset_path: null
---

## **The Link Menu**

![](images/_page_133_Picture_1.jpeg)

The Link menu provides a standard interface for receiving and supplying linked information. *Linked information* is copied information, such as a graphic image, that can be automatically updated when the original information is modified. See the *User's Guide*  for more information on working with links.

| Command           | Action                                                                                                                                                                                                                                                                                    |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Paste and Link    | If the last Copy operation was performed in an application that can<br>supply linked information, this command pastes the contents of the<br>pasteboard and links it to the original information.                                                                                         |
| Paste Link Button | If the last Copy operation was performed in an application that can<br>supply links, this command pastes a button <) that, when clicked,<br>opens the document that contains the original information. Link<br>buttons are discussed in Chapter 7, "Controls."                            |
| Publish Selection | Creates a link file. When the link file is dragged into documents<br>that can receive linked information, the end result is as if a Paste<br>and Link command had been done. This command places a<br>panel on-screen that asks the user to type in a file name or cancel<br>the command. |
| Show Links        | Highlights or unhighlights all linked information in the current<br>document. The name of this command must alternate between Show<br>Links and Hide Links, depending on the state of the document.                                                                                       |
| Link Inspector    | Brings up the Link Inspector panel, which is discussed in Chapter 5.                                                                                                                                                                                                                      |

An application that can receive linked information (one that implements one or both of the Paste and Link and Paste Link Button commands) should also implement Show Links and Link Inspector.

When the user chooses the Show Links command, the application should highlight all the , linked information in the main window, as shown in the following figure. In the window shown below, the picture at the lower left is the only visible linked information, so it's the only picture that's highlighted with a chain pattern.

![](images/_page_134_Picture_2.jpeg)