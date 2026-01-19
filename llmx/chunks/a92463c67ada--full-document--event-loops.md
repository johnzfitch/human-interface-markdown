---
chunk_index: 840
ref: "a92463c67ada"
id: "a92463c67ada0d4a749f6bfe7a044e32914f823c2805da32fb9935a2e3669ce0"
slug: "full-document--event-loops"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [474, 479]
token_estimate: 215
content_sha256: "4efcd9440491ee82219c27b742536920c52d90e9dcd67e8aa5dcdc52e4e74a67"
compacted: false
heading_path: ["Event Loops"]
symbol: null
address: null
asset_path: null
---

# Event Loops

The concept of the event loop is absolutely essential when programming for this interface. The programmer must anticipate the entire range of activities that a user might perform at any moment. The more traditional approach is to limit the user's alternatives, often by presenting a series of menus, each with limited number of alternatives, and each of which disappears (sometimes never to be found again) when the user makes a choice. Another approach is to have single buttons that on certain occasions return the user to the "main menu."

The user of the Apple Desktop Interface, on the other hand, can at any time perform a wide range of actions—quit, open a file, rearrange the icons on the desktop. To enable this enormous flexibility, programmers must also consider how to block the activities that are not appropriate at a given time.