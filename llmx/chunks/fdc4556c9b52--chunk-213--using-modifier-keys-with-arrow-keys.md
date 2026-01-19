---
chunk_index: 2447
ref: "fdc4556c9b52"
id: "fdc4556c9b52ccbd103d235c1f3a0f5d4ed36a17386e3a9a48fbb430eebf24dc"
slug: "chunk-213--using-modifier-keys-with-arrow-keys"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_213.md"
kind: "markdown"
lines: [18, 35]
token_estimate: 1147
content_sha256: "6144fceb3a51c5c276751c471dd9b9b5edac5bfdcc45f8fab0ab78681d6cc2c9"
compacted: false
heading_path: ["Appropriate Uses for the Arrow Keys","Moving the Insertion Point","Moving the Insertion Point in Empty Documents","Using Modifier Keys With Arrow Keys"]
symbol: null
address: null
asset_path: null
---

#### Using Modifier Keys With Arrow Keys  
In some cases it's appropriate to use modifier keys such as Option and Command to extend the action of moving the insertion point in a document. This allows users to move the insertion point using keyboard combinations as an alternative to the mouse. Keep in mind that these keyboard combinations are only shortcuts for mouse actions. It is *optional* to extend these behaviors to applications but it is *never* appropriate to implement only a keyboard shortcut and not provide a mouse-based way to perform the same action.  
You can support using modifier keys with arrow keys to move the input focus, extend a selection, or move objects. The most common uses of these keyboard combinations are to extend selections and to move the insertion point. The paragraphs that follow suggest typical uses for modifier key–arrow key combinations.  
The Option key and the Command key are both used as semantic modifiers with the arrow keys. A semantic modifier changes the semantic unit that the arrow keys affect. The application determines what the semantic units are. For example, in word-processing applications, semantic units are characters, words, lines, paragraphs, and documents. In general, the Option key increases the size of the semantic unit by 1 compared to the arrow keys alone, and the Command key enlarges the semantic unit again. Table 10-2 shows how the Option key and Command key could change the effect of arrow keys in a word-processing application.  
**Table 10-2** How modifier keys change the movement of the insertion point with the arrow keys  
|             | Arrow key alone     | With Option key       | With Command key or Shift key |
|-------------|---------------------|-----------------------|-------------------------------|
| Left Arrow  | Left one character  | Left one word         | To beginning of line          |
| Right Arrow | Right one character | Right one word        | To end of line                |
| Up Arrow    | Up one line         | To start of paragraph | To top of window              |
| Down Arrow  | Down one line       | To end of paragraph   | To bottom of window           |  
If there aren't any paragraphs or an additional paragraph marker after the insertion point in the document, then Option–Down Arrow can't move the insertion point to its end. In this case, you should map Option–Down Arrow to have the same action as Down Arrow. For example, if the insertion point is already at the end of the document and the user presses Option–Down Arrow, play the system beep to call the user's attention to the position of the insertion point.  
In an application (such as a spreadsheet) that represents data in an array, the basic semantic unit would be the cell. Option–Left Arrow (or Option–Right Arrow) would designate the cell to the left (or right) of the currently active cell as the new active cell. Using modifier keys with arrow keys doesn't change the data; Option–Left Arrow just causes the data to be entered and moves the selection to the next cell to the left.  
Though the use of multiple modifier-key combinations (such as Command–Option–Left Arrow) is discouraged, it's all right to use the Shift key with any one of the other modifier keys for making a selection. (See "Selecting With the Arrow Keys" on page 295 for more information.) If multiple keys must be pressed simultaneously, they should be fairly close together, otherwise, some people won't be able to use that combination.  
The Keyboard **283**  
Note that for non-Roman script systems, Command–Left Arrow and Command–Right Arrow are reserved for changing the direction of keyboard input. Specifically, Command–Right Arrow changes the keyboard layout to Roman and Command–Left Arrow changes the keyboard layout to the system script. This capability is especially useful for bidirectional script systems such as Arabic and Hebrew since it allows users to change the direction of keyboard input. See Table 4-2 in Chapter 4, "Menus," on page 128 for more information. Also, Command–Shift–Left Arrow and Command–Shift–Right Arrow move the insertion point to the beginning and end of the line, respectively.  
![](images/_page_307_Picture_3.jpeg)  
In all cases, if you can't complete a user action for some reason, provide feedback to indicate this. For example, you can flash the menu bar or play a sound on the first instance of a user action that can't be completed. You can also display an alert box that describes the situation and gives suggestions to the user about what can be done in the current context.