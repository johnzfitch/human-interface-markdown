---
chunk_index: 195
ref: "78025e2e8d9f"
id: "78025e2e8d9fbf854bd7da111c301894b2c09322f6ddba915066b8e34ffcaecc"
slug: "full-document--simplicity"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [521, 530]
token_estimate: 279
content_sha256: "e3c7d193f8a59170d66c1a93cd9461c0c60912a00e25193e68ce59a6ecfb69d3"
compacted: false
heading_path: ["A Planning and Testing Methodology","Simplicity"]
symbol: null
address: null
asset_path: null
---

## Simplicity

User interaction should be simple and easy to remember. Spend the necessary time to design a user interface that presents the best tradeoff between alternate design issues.

Once the user has become basically familiar with the human interface, if she guesses at an unknown response, she should be correct 95% of the time.

Simplicity is discussed in detail in the next section, General Program Structure.

BASIC: When a package contains several programs on a diskette, the programs should always be selectable by the user via a menu display. The user should not have to RUN (or worse, BRUN) individual programs in immediate mode to get the package to function. Each program should end by causing a "menu" program to be run, which should provide the appropriate menu display. The menu program should be a simple program which displays a menu of all programs to which the user will be given direct access, and stores information on the environment in which it runs; for example, it can set any HIMEM: or LOMEM: required by a program on its menu. An example of this is INDEX on THE SHELL GAMES diskette.