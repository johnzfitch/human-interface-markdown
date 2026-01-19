---
chunk_index: 2732
ref: "feaae470cb04"
id: "feaae470cb0448ac07e27ab0e3461bbce2aa977aae4281d05262c0236da64254"
slug: "full-document--publisher-subscriber-options"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2106, 2135]
token_estimate: 986
content_sha256: "6e9cfe1c56a2311811c635424d9945d1d3dee493572814cacdcb79b79c2ba642"
compacted: false
heading_path: ["Standard Macintosh Menus","The Edit Menu","The Clipboard","Publisher/Subscriber Options…"]
symbol: null
address: null
asset_path: null
---

#### Publisher/Subscriber Options…

The Publisher Options and Subscriber Options commands allow you to provide some choices about publishers and subscribers to the user. Publisher/Subscriber Options is a context-sensitive toggled command; the command name changes to reflect whether a publisher or subscriber is selected. If a user selects a publisher, the command should be Publisher Options. If a user selects a subscriber, the command name should change to Subscriber Options. If no area is selected, the command should appear unavailable in the last state it was in.

Figure 4-81 shows the Publisher Options dialog box. The options apply to the currently selected publisher.

**Figure 4-81** The Publisher Options dialog box

![](images/_page_142_Picture_4.jpeg)

The Cancel Publisher button allows the user to stop sending the information to an edition. The data remains unchanged in the document. The border that denotes a publisher no longer appears when the data is selected.

The Send Editions radio buttons allow the user to specify whether to automatically send a new edition when the document is saved or to send the data to the edition when the user decides to do so. The Send Edition Now button becomes available when the user clicks the Manually button. Then the user must click the Send Edition Now button to specifically send a new edition of a publisher. Information that identifies the latest edition sent appears in the area below the radio buttons.

If you provide additional options to the user, include the controls in the bottom area of the Publisher Options dialog box.

Figure 4-82 shows the Subscriber Options dialog box. The options apply to the currently selected subscriber.

**Figure 4-82** The Subscriber Options dialog box

![](images/_page_142_Picture_10.jpeg)

The Edition Manager has no provisions to let users edit subscribers directly because new editions can arrive at any time. This situation could be especially destructive if several users were working over a network with interconnected publishers and subscribers, and new editions arrived that replaced subscribers that had been edited. To make changes to a subscriber, the user must go to the publisher and make changes to it. The user can use the Open Publisher button in the Subscriber Options dialog box. This option locates the document that contains the publisher and opens it, launching the application if necessary. The document automatically scrolls to display the publisher. When the user saves changes to the document, the new contents are written to the edition file and all subscribers are updated. Because the changes are made to the original document, the user can make changes to the data without danger of losing the change in a subscriber. It's important to note that the user must have correct access privileges to the document that contains the publisher for this option to work. If a user doesn't have permission to open a file on a file server or a personal Macintosh, display an alert box to notify the user that the publisher couldn't be opened and why.

The Cancel Subscriber button allows the user to break the connection to the edition. The data remains in the document, but new editions won't be received and the borders that denote a subscriber no longer appear.

The Get Editions radio buttons allow the user to specify when new editions should be received. If the user clicks Automatically, editions arrive as they become available when the document is open or each time the document is opened if new editions are available. If the user clicks Manually, new editions are received when the user selects the subscriber, chooses Subscriber Options, and then clicks the Get Edition Now button. Information that identifies the latest edition available appears in the area below the radio buttons.

If you provide additional options to the user, include the controls in the bottom area of the Subscriber Options dialog box.