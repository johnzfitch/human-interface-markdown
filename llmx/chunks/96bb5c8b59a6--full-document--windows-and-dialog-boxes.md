---
chunk_index: 2838
ref: "96bb5c8b59a6"
id: "96bb5c8b59a66e712547b8c033d1db618712b522ebc3a792276dd03be5ab611d"
slug: "full-document--windows-and-dialog-boxes"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [4007, 4024]
token_estimate: 543
content_sha256: "d3ad83b3360de58eac5bb90e37a7deb97194accb78ebf38f92957c09854ebe72"
compacted: false
heading_path: ["Color Design of Standard Interface Elements","Windows and Dialog Boxes"]
symbol: null
address: null
asset_path: null
---

## Windows and Dialog Boxes

The windows and dialog boxes in System 7 are designed for aesthetic consistency across all monitors from black-and-white displays to 8-bit color displays. For display on color monitors, color and shades of gray have been added to the frames of windows and to user controls. The window background remains white on all systems. This updated design takes advantage of the color capabilities of the Macintosh but maintains the consistency of the Macintosh interface. On color screens, the racing stripes in the title bar and the scroll bars are gray. The user controls—close box, size box, zoom box, and scroll box—are colored to make them more apparent. The borders of inactive windows are gray and recede into the background so that the active window's black frame emphasizes its position in front of the other windows. Figure 9-1 shows a colorized window.

**Figure 9-1** A colorized window

![](images/_page_282_Picture_3.jpeg)

Figure 9-2 shows a dialog box with a colored frame, but black radio buttons and text.

**Figure 9-2** A colorized movable modal dialog box

![](images/_page_282_Picture_6.jpeg)

![](images/_page_282_Picture_7.jpeg)

The standard window definition functions display color windows and dialog boxes. Some control definition functions display in color the window's scroll bars, scroll arrows, scroll box, close box, size box, and zoom box. If you use the standard window definition functions and standard control definition functions, your application's windows will match the appearance of standard windows. If you create your own windows, be compatible with the desktop appearance by using the standard window color table and the guidelines described in this section. Be aware that users can change the colors of windows and dialog boxes by using the Color control panel. If you use the default window color table, you can be sure that the colors you use are consistent with any color that the user has access to with the Color control panel. You can use the Palette Manager to associate a color palette with a window definition. For more information, see the discussion of the Palette Manager in *Inside Macintosh*.