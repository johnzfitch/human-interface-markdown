---
chunk_index: 1285
ref: "7dbac312ad74"
id: "7dbac312ad745c276711ec9526db5e3c61918c6659b7443334143f348fd25d1a"
slug: "full-document--the-event-loop"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [320, 327]
token_estimate: 244
content_sha256: "ab0206dacfcb44dfcfda073c021db74e0125087d4485bc7224925161cf322f70"
compacted: false
heading_path: ["The event loop"]
symbol: null
address: null
asset_path: null
---

# The event loop

Applications are prepared for the user to do anything at any time.

The event loop is central to programming for the Apple Desktop Interface. The event loop is the central routine of any application. An application doesn't have to expect a certain set of events in a particular order, but constantly looks for inputs (mouse actions, keystrokes, disk insertions) that can occur in any order and to which it must respond in specific ways.

This approach to programming contrasts with programs that systematically limit the alternatives available to the user, assuring that the user follows the "right" path to the "right" place. Instead, the emphasis is on responding to each local request the user makes, leaving the responsibility for the final destination with the user. In each context, the widest possible range of user activities should be enabled. For example, there's no reason not to let the user set printing options before there's anything to print.