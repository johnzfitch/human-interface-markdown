---
chunk_index: 4099
ref: "3188360bf1df"
id: "3188360bf1dff9212c757831de072af5a1eaef9762c5260b83258cbfadf43e19"
slug: "full-document--implementing-the-preferences-panel"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1895, 1913]
token_estimate: 368
content_sha256: "f7885ded95a07d7a42982f5623083d40e9ff4b06674c34a04079cf7ada07ff72"
compacted: false
heading_path: ["5 *Panels*","**Implementing the Preferences Panel**"]
symbol: null
address: null
asset_path: null
---

## **Implementing the Preferences Panel**

![](images/_page_108_Picture_4.jpeg)

Most applications have a Preferences panel, an ordinary panel that allows the user to determine details of how the application looks and works. A user typically uses this panel only a few times. It should not be necessary to bring up the Preferences panel during normal use of the application.

Preferences typically include such things as:

- The default font size
- The format for displaying data
- Whether to make backup files
- The default size of windows
- Options that increase the power of the application
- The application's keyboard alternatives

Do *not* use the Preferences panel for anything the user might want to set from time to time during a session. Also, the contents of the Preferences panel should be valid applicationwide: They shouldn't change depending on which window or data is selected. All preferences should carry over from session to session; most will also affect the way the application works during the current session. All of an application's options must be settable in some way from within the application. For example, it isn't acceptable to have options that are settable only by using the **dwrite** command.

Preferences panels are often implemented as multiform panels to reduce their size and to organize their options. The Preferences panel is brought up by the Preferences command in the Info menu. See Chapter 6 for information on the Info menu.