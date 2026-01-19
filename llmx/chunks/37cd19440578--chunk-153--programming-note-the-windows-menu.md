---
chunk_index: 3777
ref: "37cd19440578"
id: "37cd194405784b6c11728b317912c6464ee3261349c8fbae6957b8c945b5ef2a"
slug: "chunk-153--programming-note-the-windows-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_153.md"
kind: "markdown"
lines: [11, 14]
token_estimate: 207
content_sha256: "6b19045d0fcca8b75a705f3ab3ec3c3789be9d0e4a57a6113e3ef8e04ed4b39f"
compacted: false
heading_path: ["**Programming Note: The Windows Menu**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: The Windows Menu**  
This menu and all of its functionality are provided for you. All you have to do is drag the Windows command into your main menu from the Palettes window of Interface Builder.  
The commands inserted below Arrange in Front list document windows. Each command brings one window to the front and, if possible, makes it the key window. The Application Kit creates this list and dynamically adds a command for each document window when it's opened. An example of these dynamically created commands is below. Because the Application Kit creates the command names from the title bar of each window, improperly titled windows can lead to the Windows menu becoming confusing or too wide. Window titles are discussed in "Choosing a Title" in Chapter 4.  
![](images/_page_142_Picture_1.jpeg)