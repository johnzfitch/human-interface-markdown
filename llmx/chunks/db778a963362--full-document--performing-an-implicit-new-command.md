---
chunk_index: 4130
ref: "db778a963362"
id: "db778a96336260bd1aee1504bb12241032f8916ed3c0fe87077bb497ed8eb580"
slug: "full-document--performing-an-implicit-new-command"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2281, 2290]
token_estimate: 295
content_sha256: "c5163069bfc0a363d427faee0a50386241d70686c70fac4bd96560d82876acf8"
compacted: false
heading_path: ["5 *Panels*","**Performing an Implicit New Command**"]
symbol: null
address: null
asset_path: null
---

## **Performing an Implicit New Command**

If the user starts up an application by double-clicking an application icon rather than a document icon, the application should, if appropriate, provide the user with a new document to work in (performing an implicit New command). This is much friendlier to a new user than simply putting a menu on-screen. Users should be permitted to disable this behavior through a preference.

It's almost always appropriate for general-purpose applications to perform an implicit New command. However, it's not appropriate if the application can't produce a new document without user input. It's also not appropriate if producing a new document has side effects, such as modifying the file system by creating a new folder or adding a file that might persist even if the user decided not to save the new document.

When an application is started up automatically at login or from another application, it should not perform an implicit New command.

If the user opens another document without touching the new one that was provided at startup, the application could automatically close the new one. But this is not a requirement of the user interface.