---
chunk_index: 3728
ref: "1ea0352913ce"
id: "1ea0352913ce7fb8fbcb1cb2c8c6738062b0dd39785da411732fb9d416ef3bf3"
slug: "chunk-117--writing-note-creating-on-line-help"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_117.md"
kind: "markdown"
lines: [12, 14]
token_estimate: 315
content_sha256: "c6930d9c9a7aa7cae1ae97d5057e6c5181ceac677a4cb6dbe9da5456444c5db1"
compacted: false
heading_path: ["**Programming Note: Implementing On-Line Help**","**Writing Note: Creating On-Line Help**"]
symbol: null
address: null
asset_path: null
---

#### **Writing Note: Creating On-Line Help**  
You're encouraged to reuse the contents of the help in NeXT applications such as Edit, Mail, and Workspace Manager. After copying the contents from one ofthese applications' Help panels, you can paste the contents into a file in your application's- help folder. You should then modify the help text and update the help links it contains so that the help suits your application. For example, Edit has help on working with documents, text, graphics, and color, as well as on printing and faxing. With a few changes, much of this help is appropriate for other document-based applications.  
You're also encouraged to use the design of NeXT's help. Help in NeXT applications is task-oriented, with Help-clicking serving as a way of discovering the tasks an object is used for. At the end of every help file is a list of related tasks, with links to the help for each task. The objects that have associated help are generally menu commands, standard windows, panels, and a few important buttons such as those in Mail's Compose window. If supplying this level of help isn't practical, then you should at least ensure that Help-clicking any object results in help on a relevant subject, even if the help is very general.