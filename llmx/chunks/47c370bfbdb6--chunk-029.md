---
chunk_index: 3597
ref: "47c370bfbdb6"
id: "47c370bfbdb6ad83677f76752e92859028838a6dec9d81b73e7b8bec0e457ca9"
slug: "chunk-029"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_029.md"
kind: "markdown"
lines: [1, 10]
token_estimate: 527
content_sha256: "f858e88569f11a128b17f059defaacf4dafee82c763541f1a31c4bd42f502341"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 29 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 500 -->
In the modal-tool paradigm, users can change the meaning of subsequent mouse actions by selecting an appropriate tool, often displayed in a palette with several other tools. Each tool controls a certain set of operations that are enabled only after it's chosen. For example, a graphics editor might provide one tool for drawing circles and ovals, another for rectangles, and still another for simple lines. Depending on which tool is chosen, mouse actions (clicking and dragging) will produce very different visual results. The cursor assumes a different shape for each tool, so that it's apparent which one has been selected, and the tool itself remains highlighted.  
Each tool sets up a *mode-a* period of time when the user's actions are interpreted in a special way. A mode limits the user's freedom of action to a subset of all possible actions, and for that reason is usually undesirable. But in the modal tool paradigm, the mode is mitigated by a number of factors:  
- The mode isn't hidden. The altered shape of the cursor and highlighted state of the tool make it apparent which actions are appropriate.
- The mode isn't unexpected. It's the result of a direct user choice, not the by-product of some other action.
- The way out of the mode (usually clicking in another tool) is apparent and easy. It's available to the user at any time.
- The mode mimics the way things are done in the real world. Artists and workers choose an appropriate tool (whether it's a brush, a hammer, a pen, or a telephone) for the particular task at hand, finish the task, and choose the next tool.  
The modal-tool paradigm is appropriate when a particular type of operation is likely to be repeated for some length of time (for example, drawing lines). It's not appropriate if the user would be put in the position of constantly choosing a new tool before each action.  
Below is a typical palette of modal tools, along with the cursor that shows that a mode is in effect.  
![](images/_page_31_Picture_9.jpeg)