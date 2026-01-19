---
chunk_index: 4149
ref: "849fe400e1b6"
id: "849fe400e1b6b59bc43f0631ab1ff863822127f1dbc129dcfd5e88f41155c1bf"
slug: "full-document--7-controls"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2567, 2592]
token_estimate: 676
content_sha256: "b8af6f518d1c7b85f5ed4148c0ad8a57ee7f70e880c05440c45ef0cf55061e3f"
compacted: false
heading_path: ["7! *Controls*"]
symbol: null
address: null
asset_path: null
---

# 7! *Controls*

Controls are graphical objects that users manipulate with the keyboard and mouse to give instructions to an application. They're patterned after familiar control devices from everyday life-switches, knobs, forms, gauges, and the like-and perform analogous functions. Like the dials and levers on a machine, graphical control objects let the user "operate" an application.

Every control responds visually to direct manipulation by the user-a dial turns, a button pushes in or highlights, the knob of a slider slides. Controls go beyond this direct response, however, to cause the application to do something. They, in effect, translate the user's direct manipulation into an instruction for the application. A button sets a state or initiates a program action, a slider sets a value, and so on.

Which keyboard and mouse actions a control responds to and how it reacts visually are part of the definition of the control; they're discussed in this chapter. What the control causes an application to do is part of the definition of the application; it depends solely on how the application uses the control. In this respect, graphical controls are no different from control devices in the real world. For example, identical mass-produced switches can be installed on a variety of different machines. The manufacturer of the switch provides it with a user interface; the installer gives it specific meaning for a specific machine.

The NeXTSTEP user interface has several standard controls:

- Buttons
- Menu commands
- Text fields
- Sliders
- Color wells
- Scrollers
- Browsers and selection lists

Because they're widely used, each of these controls is described in some detail in its own section. Menu commands were described in Chapter 6, "Menus." The other controls are described in the sections below.

You can also design your own controls-the Application Kit makes this relatively easy-but they should adhere to these basic design principles:

- Every control must provide immediate feedback to let the user know that an action has "taken." Just as users can look at a dial on a stove to see whether it has been turned, a graphical control must alter its appearance in response to user actions. It shouldn't depend on a reaction elsewhere in the application to give the user feedback.
- Every control should have a distinctive appearance and behavior. Don't design controls that look so similar to the canonical controls that users will confuse one with the other.
- The behavior of a control should be apparent from its appearance. After a bit of familiarity with NeXTSTEP, users should be able to easily recognize a control object and know almost instinctively how to operate it.