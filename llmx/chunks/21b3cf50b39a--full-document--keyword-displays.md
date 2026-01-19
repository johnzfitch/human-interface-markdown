---
chunk_index: 238
ref: "21b3cf50b39a"
id: "21b3cf50b39ada93aac98479c42a06553ade3346ee5d7dc8cbd1369492373b35"
slug: "full-document--keyword-displays"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [1069, 1090]
token_estimate: 396
content_sha256: "87d428ba1336248f3d313ff5b7481fe78cf3755a516951778fa3de9c7f4df3f2"
compacted: false
heading_path: ["Keyword Displays"]
symbol: null
address: null
asset_path: null
---

# Keyword Displays

(The following is a repeat of an earlier section. The keyword display is repeated here to make the document useful for reference.)

In order to type a command or list selection without prompting, the user must learn what words he can type at any one point in the program. This learning problem can be overcome in a quite straightforward manner by displaying a list of all options then available. Typically, this can be done by creating a display similar to the standard menu format, with the center region devoted to the list of words:

| Commodity Anal    | yser Belly Processes    | Pork Bellies |
|-------------------|-------------------------|--------------|
| Commands:         | Inventory Types:        |              |
| display           | complete l              | bellies      |
| graph             | partial belli           | ies          |
| compute           | dancing be              | ellies       |
| buy               |                         |              |
| sell              |                         |              |
| eat               |                         |              |
| delete            |                         |              |
| Type your instruc | ion and press RETURN: _ |              |

Options: ESCAPE to leave OPEN-APPLE-? for help

As the available options change, so do the options displayed. Thus, the user knows at every point exactly what she can select. (The display of command words could be made optional through the novice/expert flag; variable lists of words, such as file names, should always be visible.)