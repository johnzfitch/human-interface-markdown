---
chunk_index: 3723
ref: "a0b7aefcdaed"
id: "a0b7aefcdaed1c4ba2079e255732377a6cc3932d422960b43efd41bf7568581d"
slug: "chunk-114--description"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_114.md"
kind: "markdown"
lines: [20, 39]
token_estimate: 646
content_sha256: "642a1018c385d9c5ea81decc1262f1c20943f3a22d9e306420fa6f90ece356e3"
compacted: false
heading_path: ["**Programming Note: Customizing Application Kit Panels**","**Panel**","**Description**"]
symbol: null
address: null
asset_path: null
---

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