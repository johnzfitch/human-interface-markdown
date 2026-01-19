---
chunk_index: 4095
ref: "35f06c6212a9"
id: "35f06c6212a984572a826667005291117b7d51f140696da125b81640f8c5dfb6"
slug: "full-document--writing-note-creating-on-line-help"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1863, 1868]
token_estimate: 315
content_sha256: "81ac754f126ceab5176d83456cf85a2ee87a2af91b9eabea598252cfb6c6459a"
compacted: false
heading_path: ["5 *Panels*","**Using the Help Panel**","**Programming Note: Implementing On-Line Help**","**Writing Note: Creating On-Line Help**"]
symbol: null
address: null
asset_path: null
---

#### **Writing Note: Creating On-Line Help**

You're encouraged to reuse the contents of the help in NeXT applications such as Edit, Mail, and Workspace Manager. After copying the contents from one ofthese applications' Help panels, you can paste the contents into a file in your application's- help folder. You should then modify the help text and update the help links it contains so that the help suits your application. For example, Edit has help on working with documents, text, graphics, and color, as well as on printing and faxing. With a few changes, much of this help is appropriate for other document-based applications.

You're also encouraged to use the design of NeXT's help. Help in NeXT applications is task-oriented, with Help-clicking serving as a way of discovering the tasks an object is used for. At the end of every help file is a list of related tasks, with links to the help for each task. The objects that have associated help are generally menu commands, standard windows, panels, and a few important buttons such as those in Mail's Compose window. If supplying this level of help isn't practical, then you should at least ensure that Help-clicking any object results in help on a relevant subject, even if the help is very general.