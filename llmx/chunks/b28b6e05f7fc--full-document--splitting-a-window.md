---
chunk_index: 2763
ref: "b28b6e05f7fc"
id: "b28b6e05f7fc71d58490283c6689f56748cedeee5f4ac151642792f8f1de72a9"
slug: "full-document--splitting-a-window"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2773, 2792]
token_estimate: 407
content_sha256: "f61169c7bb8d7a75357e8fd6f94b73f4658ed335e3f0c84e77e63de7f8c6452d"
compacted: false
heading_path: ["Window Behaviors","Splitting a Window"]
symbol: null
address: null
asset_path: null
---

## Splitting a Window

You can provide the ability for people to look at different parts of a document simultaneously by implementing a split bar. The **split bar** is a control, five pixels high by the width of the scroll bar, contained in the scroll bar. Users drag the split bar to separate a document into separate scrolling sections, called **window panes.** A **split line** appears to visually separate the panes. (Note that there should a one-pixel space between the two lines that make up the split line.) For example, the user might want to look at the opening paragraphs and review the conclusion of a document in a word-processing

program at the same time. In a programming environment, you might want to see the include statements at the beginning of a document while looking at routines in another part of the document. Split windows are useful for copying data from one part of a document and pasting it into another part. The user drags the split bar to a location in the scroll bar where the new pane is to begin. To remove a window pane, the user drags the split bar to within three pixels of the top or right of the scroll bar. Figure 5-40 shows a window split into two panes.

**Figure 5-40** A split window

![](images/_page_194_Picture_4.jpeg)

The split bar should be large enough for the user to accurately place the pointer on it, but not so large that it attracts attention. Figure 5-41 shows an example of the correct size for a split bar and some comparison sizes.

**Figure 5-41** Split bar size

![](images/_page_194_Picture_7.jpeg)

Window Behaviors **171**

![](images/_page_195_Picture_2.jpeg)