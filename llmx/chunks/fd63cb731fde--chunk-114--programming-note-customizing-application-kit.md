---
chunk_index: 3721
ref: "fd63cb731fde"
id: "fd63cb731fdec77653321225bbceb58cf4c374c7be206512a31a8da2a73702ad"
slug: "chunk-114--programming-note-customizing-application-kit"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_114.md"
kind: "markdown"
lines: [7, 18]
token_estimate: 897
content_sha256: "f3b1f22eb518e439f820e992cc2526a768b928a7e802efd78760cf06d1c6e397"
compacted: false
heading_path: ["**Programming Note: Customizing Application Kit Panels**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Customizing Application Kit Panels**  
To customize panels that are implemented by the Application Kit, you should first construct a View containing the information and controls you want to add. You can then add the View by sending it to the panel in a **setAccessoryView:** message.  
The following table lists and describes the standard panels. After the table are sections describing how to implement each panel that isn't completely implemented by the Application Kit.  
| Panel<br>Close | Description<br>An attention panel that should come up when the user tries to close<br>a document that has unsaved changes. See "Implementing the Close<br>Panel," later in this chapter, for more information.                                                                                                                                                             |
|----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Colors         | An ordinary panel that's provided by the Application Kit. It lets<br>the user preview and specify colors in any of the following<br>modes: color wheel, grayscale, red-green-blue (RGB),<br>cyan-magenta-yellow-black (CMYK), hue-saturation-brightness<br>(HSB), custom palette (which loads an image from which the user<br>can choose colors), and custom color lists . |
|                | . A Colors panel sometimes works with color wells. See "Color<br>Wells" in Chapter 7, "Controls," for information on color wells. See<br>"The Font Menu" in Chapter 6 for information on the command that<br>brings up the Colors panel.                                                                                                                                   |
| Find           | An ordinary panel that lets the user enter a string for an application<br>to search for. See "Implementing the Find Panel," later in this<br>chapter, for more information on this panel.                                                                                                                                                                                  |
| Font           | An ordinary panel that's provided by the Application Kit. It lets the<br>user preview fonts and change the font of the currently selected text.<br>See "The Font Menu" in Chapter 6 for more information on the<br>interface to fonts.                                                                                                                                     |
| Help           | An ordinary panel that's provided by the Application Kit. You<br>should use this panel to display anyon-line help provided by your<br>application. This panel displays information that can contain text,<br>graphics, and link buttons (which lead to other information). See<br>"U sing the Help Panel," later in this chapter, for information on<br>creating help.     |
| Info           | An ordinary panel that displays information about the application.<br>See "Implementing the Info Panel," later in this chapter, for more<br>information on this panel.                                                                                                                                                                                                     |  
( *continued)*