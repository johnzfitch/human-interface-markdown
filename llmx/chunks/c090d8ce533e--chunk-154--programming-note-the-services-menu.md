---
chunk_index: 3780
ref: "c090d8ce533e"
id: "c090d8ce533ed5ff99d6ff8bb0bcf206370655f445507e4893117cd7cdadaeae"
slug: "chunk-154--programming-note-the-services-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_154.md"
kind: "markdown"
lines: [8, 10]
token_estimate: 174
content_sha256: "48ae5ae71ac21f3c63fc18b8d70946f5ca6d3553cf0d60df9b5492d4b3f5afdb"
compacted: false
heading_path: ["**Programming Note: The Services Menu**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: The Services Menu**  
To take advantage of services provided by other applications, you should first drag the Services menu from the Palettes window of Interface Builder. Then, if you use the Text object in your application, your application automatically gets many services. Your application can get more kinds of services if you write a few lines of code.  
To put its services into other applications, your application advertises its services in a section of its executable file or in its file package. (File packages are special folders that look and behave like files.) These services are automatically included in the menus of any applications that can accept them.