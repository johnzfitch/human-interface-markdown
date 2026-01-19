---
chunk_index: 1859
ref: "77652174b19c"
id: "77652174b19ccf18ef227706a23982b1b40bf805033eda3bf6c6a86f15a0a0aa"
slug: "full-document--a-strategy-for-programming"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [566, 575]
token_estimate: 266
content_sha256: "459dfd0f7a0d505ea74a7552bb33b8fd340038826f6dffeba78dc400ad8816c2"
compacted: false
heading_path: ["A strategy for programming"]
symbol: null
address: null
asset_path: null
---

# A strategy for programming

The Apple Desktop Interface relies on some distinctive models for programming, some of which are unfamiliar even to experienced programmers.

To help the programmer make use of this interface, and to carry through in these models, some Apple hardware systems provide an abundance of tools in ROM. The developer derives two major advantages from using ROM-based tools and resources: compatibility and efficiency. The more a program bypasses or replaces these tools and resources, the more likely that sooner or later it will be incompatible with new products or features.

Although <sup>a</sup> developer might know <sup>a</sup>more direct way of getting information or performing an operation, using system-provided features ensures hardware independence. For example, always reference the proper data structures to determine the current size of a screen rather than using the constant values for current hardware.

The next sections deal with some important programming issues that are at the heart of the Apple Desktop Interface.