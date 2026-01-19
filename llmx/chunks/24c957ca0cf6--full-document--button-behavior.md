---
chunk_index: 2793
ref: "24c957ca0cf6"
id: "24c957ca0cf62c32d1ba289f721a4f2828932a57333c59e61776cc8ec679a27f"
slug: "full-document--button-behavior"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [3217, 3238]
token_estimate: 857
content_sha256: "d1adfd76c0b9e6eb3107fc1923145b6eb038a5f73fb2dd87b1e73cb3d308fab6"
compacted: false
heading_path: ["Standard Toolbox Controls","Buttons","Button Behavior"]
symbol: null
address: null
asset_path: null
---

#### Button Behavior

When the user clicks a button, the button highlights (inverts) to give visual feedback to the user that indicates which item has been clicked. All alert boxes and modal dialog boxes that use the ModalDialog procedure exhibit this behavior. If you implement your own controlling mechanism for dialog boxes or alert boxes, be sure to include this behavior. For buttons that are activated by using a keyboard sequence, the Dialog Manager inverts the button for eight ticks, which is long enough for the user to see that the keyboard event has taken effect. (You must invert the Cancel button when the user presses Command-period or the Escape key; the Dialog Manager does not handle these events.) If the user presses the mouse button while the pointer is over a button, the button stays inverted until the user releases the mouse button or moves the pointer away from the button. The button tracks the mouse movement as long as the user keeps the mouse button depressed. If the user moves the pointer back over the button, it is highlighted. If the user releases the mouse button while the pointer is not over the button, nothing happens. Figure 7-2 shows a button that is highlighted to provide feedback.

**Figure 7-2** A highlighted button

![](images/_page_228_Picture_9.jpeg)

The **default button** should be the button that represents the action that the user is most likely to perform if that action isn't potentially dangerous. To denote a default button, draw an additional border of three black pixels, separated by a border of one white pixel, around it to let the user know that it is the default. (In alert boxes, the Macintosh Toolbox outlines the default button.) When the user presses the Enter key or the Return key, your application should respond as if the user clicked the default button.

![](images/_page_229_Picture_3.jpeg)

Don't use a default button if the most likely action is dangerous—for example, if it causes a loss of user data. When there is no default button, pressing Return or Enter has no effect; the user must explicitly click a button. This guideline protects users from accidentally damaging their work by pressing Return or Enter. You can consider using a safe default button, such as Cancel.

Don't display a default border around any button if you use the Return key in text entry boxes. Having two behaviors for one key can confuse users and make the interface less predictable.

In addition to the action button or buttons, it's a good idea to include a Cancel button. This button returns the computer to the state it was in before the dialog box appeared. It means "forget I mentioned it." Always map the keyboard equivalent Command-period and the Esc (Escape) key to the Cancel button. These keyboard equivalents, along with Return and Enter, are accelerator keys and serve the purpose of letting the user respond quickly to a dialog box or an alert box. In general, it's not a good idea to assign other keyboard equivalents to buttons. If you find it useful to assign keyboard equivalents to some buttons that are used very often in your application, be sure to follow the guidelines in Chapter 4, "Menus," in the section "Keyboard Equivalents," which begins on page 128.

See the chapter "Dialog Manager" in *Inside Macintosh: Macintosh Toolbox Essentials* for information about implementing these behaviors for buttons.

![](images/_page_229_Picture_8.jpeg)