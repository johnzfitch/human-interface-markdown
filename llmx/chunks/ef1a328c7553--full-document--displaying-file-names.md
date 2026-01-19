---
chunk_index: 4197
ref: "ef1a328c7553"
id: "ef1a328c75532877fc2d73900dbcade832b7dfbab77c128f843a3b7199798a8d"
slug: "full-document--displaying-file-names"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [3170, 3192]
token_estimate: 227
content_sha256: "a2d7598ba68c35b0ec027f8f9cd3ddd03654ebc1a376fbc87233828bb378f418"
compacted: false
heading_path: ["*The I nterface to the File System*","**Displaying File Names**"]
symbol: null
address: null
asset_path: null
---

## **Displaying File Names**

File names are often displayed in a browser, where the user can see the path leading to the file. However, sometimes it's necessary to use only text for the file's name and path. In this case, the file's name should usually be displayed followed by two spaces, an em dash, two more spaces, and then the path. For example:

```
job Records - INet/machine/home/records
```

However, when there isn't much space to display the file name-as in a menu commandthe path can be shortened to the minimum necessary to differentiate the file name. The part of the path that isn't shown should be replaced with three dots.

For example, if one file called jobRecords is listed in limited space, it should be listed as:

```
jobRecords
```

If two files called jobRecords are listed in limited space, they might be listed as:

```
job Records - .. ./records 
job Records - .. ./backup
```