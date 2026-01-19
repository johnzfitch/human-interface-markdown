---
chunk_index: 1619
ref: "4953acfdbce6"
id: "4953acfdbce6cf504b94b2a6715dbad2eb5d0afd5c001ccff1add8007945a593"
slug: "chunk-019--applications-are-prepared-for-the-user-to-do"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/chunks/chunk_019.md"
kind: "markdown"
lines: [18, 20]
token_estimate: 242
content_sha256: "26c004dc6d6f4efaba8cde78cf75271abead83b978970e8449472b823c3ad5f1"
compacted: false
heading_path: ["The event loop","Applications are prepared for the user to do anything at any time."]
symbol: null
address: null
asset_path: null
---

#### Applications are prepared for the user to do anything at any time.  
The event loop is central to programming for the Apple Desktop Interface. The event loop is the central routine of any application. An application doesn't have to expect a certain set of events in a particular order, but constantly looks for inputs (mouse actions, keystrokes, disk insertions) that can occur in any order and to which it must respond in specific ways.  
This approach to programming contrasts with programs that systematically limit the alternatives available to the user, assuring that the user follows the "right" path to the "right" place. Instead, the emphasis is on responding to each local request the user makes, leaving the responsibility for the final destination with the user. In each context, the widest possible range of user activities should be allowed. For example, there's no reason not to let the user set printing options before there's anything to print.