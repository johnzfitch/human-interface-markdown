---
chunk_index: 3829
ref: "e3db43c9a08f"
id: "e3db43c9a08fbde4dd950e1151ab98b806bcbef9efadea176534a6942503c953"
slug: "chunk-185"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_185.md"
kind: "markdown"
lines: [1, 8]
token_estimate: 453
content_sha256: "338a9840b5bf4c012abc936c27b75b4d335aa2c02e66a35b9e8321ec0d98f301"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 185 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 427 -->
Applications sometimes need to create files and folders for a user, other than as the result of a Save command.  
If the files are associated with a particular document, they should be grouped with that document and placed in a file package.  
Otherwise, where the files are located and what they're named depends on whether the user needs to have direct access to them:  
• If the user never needs to get at the files or folders independently of using the application that creates them, they should be placed in a folder named .... /.Applnfo. If an application needs to create many such files, it should put them in its own folder in .... /.Applnfo. For example, if an application named My App needs to create many unrequested files, it should put them in a folder called .... /.Applnfo/My App. If the .... /.Applnfo folder doesn't already exist, the application should create it.  
• If the user might sometimes need to get at the files or folders independently of the application that creates them (for example, template files), they should be placed under -/Library. You should name each file or folder so that the user can easily tell which application put it there.  
The guiding principle here is that the user's home folder belongs to the user. An application shouldn't leave anything there that belongs to it, not to the user. When the application must create unrequested files and folders, it should put them where the user can find them but where they aren't likely to get in the user's way.  
Note: You should generally use the defaults system instead of files to store small amounts of data.· The functions supporting the defaults system are described in the *NeXTSTEP General Reference* manual.