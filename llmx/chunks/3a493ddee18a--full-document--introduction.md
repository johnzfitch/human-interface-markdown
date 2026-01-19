---
chunk_index: 1309
ref: "3a493ddee18a"
id: "3a493ddee18a895d98f97231cf4f57c1b08b0466e3caeb38287cd489d642f57e"
slug: "full-document--introduction"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [615, 624]
token_estimate: 471
content_sha256: "a2cf5755bc06c8fa03dd6991fee750767e3a8d1f61d62022e22e75597fb362b9"
compacted: false
heading_path: ["Summary","Introduction"]
symbol: null
address: null
asset_path: null
---

## Introduction

This chapter provides detailed specifications of the same elements that were introduced in Chapter 2. If you follow these specifications and take advantage of standard ROM-based tools, your applications will be as compatible as possible with other applications for the same hardware.

The active application controls all communication between the user and the computer. For your application to have the "look and feel" of the Apple Desktop Interface, it must include the standard interface elements.

The Finder is a program that lets the user organize, copy, move, rename, and delete documents, and launch other applications. When the user, from the Finder, opens an application or a document belonging to an application, that application becomes active and displays its document window. In a single-application environment, only one application can be active at a time, and it has control of all windows (except desk accessories), and the user must return to the Finder to change from one application to another. Multiprocessing will eventually allow several applications to share the screen, each having control over its own windows, and the user will be able to switch applications directly.

Each document is a unified collection of information—a business letter, list, worksheet, chart, animation sequence, or piece of music. A complex application, such as a data base system, might require several related documents. Some documents can be processed by more than one application; but each document has a principal application, which is usually the one that created it. If other applications can process the same document, they are called the document's secondary applications. Opening a document, whether through a menu or through double-clicking its icon, launches the application that originally created that document (assuming the application is available).