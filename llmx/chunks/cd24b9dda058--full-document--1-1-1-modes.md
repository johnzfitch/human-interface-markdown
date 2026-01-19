---
chunk_index: 282
ref: "cd24b9dda058"
id: "cd24b9dda058784f33aaf1b46c5d93f420058a689d84d2352ee37af792a93d20"
slug: "full-document--1-1-1-modes"
path: "marker/1983 Lisa UI Guidelines/full_document.md"
kind: "markdown"
lines: [53, 75]
token_estimate: 576
content_sha256: "c7f02e76510426cd2366abac33416c46903277ff13988fae2c3c3809f29a11a6"
compacted: false
heading_path: ["Chapter 1 Overview","1.1.1 Modes"]
symbol: null
address: null
asset_path: null
---

## 1.1.1 Modes

A mode is a state of the system that the user has to formally begin and end, and that restricts the operations he can perform while it is in effect. Experience has shown that it is hard for users, especially naive users, to learn and to use mode-based systems because of the number of arbitrary operations they have to memorize.

We have avoided modes in the Lisa user interface, but we haven't eliminated them entirely. We have used them wherever their value as the solution to a problem outweighs their inconvenience. Some examples are:

- 1) When the application sends the user an alert message warning him of a potentially serious problem, the user must acknowledge the message and deal with the problem before doing anything else. An example is entering an invalid formula in LisaCaic. The user must correct the formula before making a selection outside the cell.
- 2) when the cost of an operation in disk space, memory, or time is high, a mode can help ensure that the user's intentions are completely clear before

1-1

Source: David T Craig

Page 0003 of 0024

Overview

the application performs the operation. For example, in LisaList, adding or removing a column is a major operation because it restructures the data base. Therefore, the user must bring up a special table to specify the change, and then explicitly indicate when she is ready to add or remove the columns.

3) Some modes are used because they correspond to the most natural way to do something. An example of this is the drawing modes in LisaDraw. Without modes, LisaDraw would not be able to give appropriate feedback while the user draw a free-hand curve or a straight line. To make the modes more natural, the metaphor of a paint palette has been introduced.

Some things that might appear to be modes really aren't. In particular, toggling a global switch does not necessarily put the user in a mode. The criterion is whether the switch restricts what the user can do. For example, the Show Margin/Tab Ruler command in Lisawrite doesn't create a mode, because it doesn't prevent the user from doing something he could otherwise have done. On the other hand, Show Formulas & Values in LisaCalc is a mode because, when this option is in effect, the user can't edit cells. This type of mode should be avoided.