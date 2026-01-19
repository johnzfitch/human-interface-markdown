---
chunk_index: 1283
ref: "ec0aa60a4891"
id: "ec0aa60a48917d56118fa51a487f68bf93cf978eb463c531beb4d0aaae009620"
slug: "full-document--a-strategy-for-programming"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [281, 290]
token_estimate: 260
content_sha256: "52df4c179475acf86233a960fc30db47091ec5da98c22b78cc0155524e5c46bf"
compacted: false
heading_path: ["A strategy for programming"]
symbol: null
address: null
asset_path: null
---

# A strategy for programming

The Apple Desktop Interface relies on some distinctive models for programming, some of which are unfamiliar even to experienced programmers.

To help the programmer make use of this interface, and to carry through in these models, some Apple hardware systems provide an abundance of tools in ROM. The developer derives two major advantages from using ROM-based tools and resources: compatibility and efficiency. The more a program bypasses or replaces these tools and resources, the more likely that sooner or later it will be incompatible with new products or features.

Although a developer might know a more direct way of getting information or performing an operation, using system-provided features ensures hardware independence. For example, always reference the proper data structures to determine the current size of a screen rather than using the constant values for current hardware.

The next sections deal with some important programming issues that are at the heart of the Apple Desktop Interface.