---
chunk_index: 4006
ref: "8fc4dedf503b"
id: "8fc4dedf503bfdc60ce6e9d157c6f8640caca000f13d6a148a32a2fb9afd37b0"
slug: "full-document--when-to-use-multiple-clicking"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [989, 1000]
token_estimate: 321
content_sha256: "c55bd8b9e1195ce62b236bc2dd3aa95d627903aefd56ef5a0b7bd6b8e512a259"
compacted: false
heading_path: ["*Introduction*","**When to Use Multiple-Clicking**"]
symbol: null
address: null
asset_path: null
---

## **When to Use Multiple-Clicking**

You should use double-clicking only for actions that logically extend the action of a single click, and triple-clicking only for actions that extend a double-click. There are two reasons for this rule, one philosophical, the other programmatic:

• Complex mouse actions are best remembered and understood when they appear to grow naturally out of simpler actions.

• Every double-click includes a single click (the first click in the sequence), and every triple-click includes a double-click. At the time an application receives one click, it can't know that any others are on their way. So it must first act on the single click, then the double-click, then the triple-click.

For example, double-clicking an icon in a Workspace Manager window picks out that icon just as a single click would. It then goes on to open the application associated with the icon. A single click in text selects an insertion point, a double-click extends the selection to a word, and a triple-click extends it further to a full line, sentence, or paragraph.

Quadruple clicks (and above) become increasingly difficult for users to produce or understand. They're neither used nor recommended in the NeXTSTEP user interface. Triple-clicks should be used only sparingly.