---
chunk_index: 4117
ref: "bea24962574b"
id: "bea24962574b9a22f847a5db6e445733a6f7eeaea86a2916cd733dd496fe2cea"
slug: "full-document--commands-that-bring-up-panels"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2108, 2121]
token_estimate: 594
content_sha256: "9f46f91e7a97787d40fc431edc65f193d3f98aead38b54979533f3567dc925bc"
compacted: false
heading_path: ["5 *Panels*","**Commands that Bring Up Panels**"]
symbol: null
address: null
asset_path: null
---

## **Commands that Bring Up Panels**

With one exception, a command that always brings up a panel must have three dots immediately following its name (for example, "Preferences ... "). The exception happens when the panel is a warning panel-such as one that comes up when the user tries to revert to a saved version of a document. Because the user could complete the action if the warning panel weren't there, it's inaccurate to imply that the command brings up a useful panel. Also, users who are new to an application sometimes tend to look at all of its panels (by choosing menu commands with " ... "). You don't want to encourage users to choose commands that are so dangerous that they require warning panels. For example, the Workspace Manager Log Out command doesn't have three dots, even though it always brings up a warning panel.

Do *not* put three dots after commands that only bring up a standard window (like the New Viewer command in the Workspace Manager, or the New command in the standard Document menu).

**Note:** Use three periods (not the ellipsis character) to produce the three dots.

If the purpose of a command is to perform an action, and the panel comes up only to help complete the action, then the command should be named for the action, not for the panel. (The panel is then given a name that reflects the command name.) In this case, use the guidelines for naming described earlier in "Commands that Perform Actions." For example, the standard Save, Save As, and Save To commands are action commands that happen to bring up a panel (which is called the Save panel).

If the purpose of the command is to bring up the panel, then the command is named after the panel. This usually results in a noun phrase as a name, instead of the verb phrase that's usually used for action commands. For example, the Preferences command brings up the Preferences panel, and the Spelling command brings up the Spelling panel.

A command that brings up a panel shouldn't usually have *Panel* in its name, since the three dots already indicate that it brings up a panel. However, you can add *Panel* if the command's name would otherwise be identical to another command's name. For example, when the command that brings up the Info panel is in the Info menu, the command is named Info ~anel. When an application has no Info menu, the command is named just Info.