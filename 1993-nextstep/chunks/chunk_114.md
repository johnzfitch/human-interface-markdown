<!-- Chunk 114 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 1778 -->
Some panels show up in many different applications. For example, every application must have an Info panel, which gives certain kinds of general information about the application. Text processing applications also have a Font panel, which lets the user set the font of the text selection. .  
This section describes all the standard panels. Some of them you have to create from scratch, using the guidelines in this section. Others are provided by the Application Kit. If a standard panel exists for functionality in your application, you should use it rather than designing your own.  
You can customize Application Kit panels, if necessary, by adding controls and information to what the Application Kit provides. For example, the Open panel on the left, below, has a check box added to it. Compare it to the normal Open panel on the right.  
![](images/_page_100_Picture_4.jpeg)  
![](images/_page_100_Picture_5.jpeg)  
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
#### **Panel**  
#### **Description**  
Link Inspector  
An ordinary panel that's provided by the Application Kit. It lets the user get and set attributes of the selected linked information. If your application's documents can receive linked information, then it should have this panel. See "Using the Link Inspector Panel," later in this chapter, for more information. "The Link Menu" in Chapter 6 has more information about links.  
Open  
An attention panel provided by the Application Kit. It lets the user specify the name of a file to open. See "Using the Open Panel," later in this chapter, for more information. The Document menu's Open command brings up this panel, as described in Chapter 6.  
Page Layout  
An Application Kit panel that queries the user for information that's needed for displaying the document on-screen, as well as for printing. It's brought up by a command in the Format menu, as described in "The Format Menu" in Chapter 6. This panel can be replaced by one more appropriate to your application, especially if your application has extensive page layout capabilities.  
Preferences  
An ordinary panel that allows the user to determine details of how the application looks and works. See the section, "Implementing the Preferences Panel," later in this chapter, for more information.  
Print  
An attention panel that's provided by the Application Kit. This panel comes up every time the user prints a document or other data. After specifying the information needed for printing, the user can do any of the following: send the output to a printer; save the output to a PostScript file, instead of printing it; send the output to a fax modem, instead of a printer; preview on-screen what will be printed; cancel any of the above actions, even after they've started. The main menu's Print command brings up this panel, as described under "The Main Menu" in Chapter 6.  
Quit  
An attention panel that should come up when the user tries to quit an application that has unsaved or uncompleted work. See "Implementing the Quit Panel," later in this chapter, for more information.  
( *continued)*  
**Panel Description**  
Save An attention panel that's provided by the Application Kit. It queries  
> the user for the name of a file to save to. See "Using the Save Panel," later in this chapter, for more information. See "The Document Menu" in Chapter 6 for information on when the Save panel is used.  
Spelling An ordinary panel provided by the Application Kit to help the user  
check the spelling of text. See "Checking Spelling" in Chapter 6 for  
more information.