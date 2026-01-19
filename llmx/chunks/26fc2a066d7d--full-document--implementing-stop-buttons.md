---
chunk_index: 4163
ref: "26fc2a066d7d"
id: "26fc2a066d7d28593c59e019f2272c58075f16929d507dee14fe21ae7eb03e65"
slug: "full-document--implementing-stop-buttons"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2728, 2755]
token_estimate: 262
content_sha256: "25007edf40cd43dbecb2a719e9d0fc5e1e330a0f58c872fd77b6b027e12f39c9"
compacted: false
heading_path: ["7! *Controls*","**Implementing Stop Buttons**"]
symbol: null
address: null
asset_path: null
---

## **Implementing Stop Buttons**

If an action might take a while, then the user should be able to cancel it by holding the Command key while pressing the period (.) key (as described in Chapter 3, "User Actions: The Keyboard and Mouse"). In addition, sometimes it's convenient for buttons that perform a time-consuming action to have a stop state, to make it more obvious to users that they can interrupt the action.

If you implement a button with a stop state, the button's appearance should change as shown below.

![](images/_page_154_Picture_8.jpeg)

before clicking

![](images/_page_154_Picture_10.jpeg)

during first click

![](images/_page_154_Picture_12.jpeg)

after first click

![](images/_page_154_Picture_14.jpeg)

during second click (if any)

![](images/_page_154_Picture_16.jpeg)

after action is finished or canceled

The button's action should be started when the user completes the first click (by releasing the mouse button). Similarly, the button's action should be stopped when the user finishes clicking the stop button.