---
chunk_index: 289
ref: "f9bdfd91648d"
id: "f9bdfd91648d4209ae15ea4105d41e086caa23ecf7fb856f38bba8af5971f044"
slug: "full-document--1-3-2-graphics"
path: "marker/1983 Lisa UI Guidelines/full_document.md"
kind: "markdown"
lines: [125, 140]
token_estimate: 279
content_sha256: "faab70dab52880962908e90c81383466dc85194aaf0addeb2f3ee7bcb0a79262"
compacted: false
heading_path: ["Chapter 1 Overview","1.3.2 Graphics"]
symbol: null
address: null
asset_path: null
---

## 1.3.2 Graphics

The graphics style is used for information that is conveyed through pictures rather than words. In some products, such as LisaDraw, the user draws pictures using the mouse; in others, such as the Desktop Manager, the user manipulates pictures drawn by the application. A graphics application can be thought of as a collection of objects that are either separate or arranged in groups. A separate object can be operated on without affecting any of the other objects.

A graphics object is either a geometrical shape (as in LisaDraw) or a bit map (as in the Desktop Menager).

Figure 1-3 snows a window containing a typical graphics document (from LisaDraw).

![](images/_page_6_Picture_8.jpeg)

Floure 1-3. LisaDraw Document

Details: A geometrically defined object can be scaled more smoothly than a bit map, but a bit map object can show finer detail.

Implementation: In the Toolkit, geometrically defined objects are supported by the Structured Graphics building block, and bit map graphics are supported by the Bit map graphics building block. Quickdraw is also available for custom graphics.