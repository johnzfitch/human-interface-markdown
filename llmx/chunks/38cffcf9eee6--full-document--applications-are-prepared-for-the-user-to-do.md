---
chunk_index: 1862
ref: "38cffcf9eee6"
id: "38cffcf9eee6745f3e32e8b7e4ad5b9fa23753ca99d2967998537c9da84dd171"
slug: "full-document--applications-are-prepared-for-the-user-to-do"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [606, 611]
token_estimate: 241
content_sha256: "551478277d3bdc4f669e4145b4bd57f36d66c2f8c8f6be754164a265523b5618"
compacted: false
heading_path: ["Modelessness","The event loop","Applications are prepared for the user to do anything at any time."]
symbol: null
address: null
asset_path: null
---

#### Applications are prepared for the user to do anything at any time.

The event loop is central to programming for the Apple Desktop Interface. The event loop is the central routine of any application. An application doesn't have to expect a certain set of events in a particular order, but constantly looks for inputs (mouse actions, keystrokes, disk insertions) that can occur in any order and to which it must respond in specific ways.

This approach to programming contrasts with programs that systematically limit the alternatives available to the user, assuring that the user follows the "right" path to the "right" place. Instead, the emphasis is on responding to each local request the user makes, leaving the responsibility for the final destination with the user. In each context, the widest possible range of user activities should be allowed. For example, there's no reason not to let the user set printing options before there's anything to print.