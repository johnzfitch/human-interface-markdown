---
chunk_index: 2664
ref: "8402d3b98a5d"
id: "8402d3b98a5dd172d7b3fd6c4b327b3128ee2a6085101488ce2e56ce6053b7ed"
slug: "full-document--implementing-preferences"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1063, 1070]
token_estimate: 317
content_sha256: "2bf2ee607a455ed5da1cbb899e6ddae77b4db2baa5d4cc0fb8ea36f7a7dbe696"
compacted: false
heading_path: ["Managing Complexity","Implementing Preferences"]
symbol: null
address: null
asset_path: null
---

## Implementing Preferences

Preference settings are user-defined parameters that your software remembers from session to session. Preferences can be a way for your application to offer choices to users about how the application runs. Preferences often affect the behavior of the application or attributes of the content created with the application.

In order to reduce the complexity of your application, make decisions about which features to implement as preferences based on what your users really need. The key is to implement as preferences only those features that your users find useful. In other words, avoid creating one large dialog box with all the preferences you can think of. Instead, eliminate the settings that are special cases of a behavior or an attribute and build in flexible features as a part of your application.

A preference should be a setting that the user changes *infrequently*. If you provide choices to users that they will change many times in a work session, you should implement those choices in a menu or other interface element to which the user has easy, modeless access. By choosing the right way to implement a feature, you can give users the flexibility to choose, in their own language, their preferred method of working.