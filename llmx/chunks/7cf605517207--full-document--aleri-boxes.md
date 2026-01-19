---
chunk_index: 1335
ref: "7cf605517207"
id: "7cf605517207107f7ec1daa1653966a223d7bcea54faf51df16bd2d7eeef1a17"
slug: "full-document--aleri-boxes"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [932, 964]
token_estimate: 957
content_sha256: "46ebc392ccc5d4e0dc354ad13851270b9b0a7e5acd1f237c488b28017cfedfc6"
compacted: false
heading_path: ["Controls, dialogs, and alerts","Dialogs","**Alerts**","Aleri boxes"]
symbol: null
address: null
asset_path: null
---

#### Aleri boxes

An alert box resembles a modal dialog box. (See Figure 20.) The only way the user can respond is by clicking buttons or by pressing Enter or Return. Alert boxes might contain dials and buttons but usually not text fields, radio buttons, or check boxes.

Note the recommended general arrangement of the elements. The icon is at the left, with the message text to the right. The buttons are below the message, with the default button, boldly outlined, at the lower right. The default is the likliest or safest response, and can be chosen by simply pressing Return or Enter.

The way to be sure the default button is really "safe" is to word the message carefully. Messages in alert boxes must be brief, informative, and friendly without being misleading. If the alert is warning the user of a serious situation, it must be made clear—not hidden in a polite phrase. Messages should be phrased so that the user can easily answer them, and the wording should reflect the user's point of view, not the programmer's.

![](images/_page_65_Picture_0.jpeg)

Figure 22 A typical alert box

There are three classes of alert boxes, each for a different kind of situation and each having its own icon. (See Figure 23.)

- Note. Provides information about situations that have no drastic effects. The user usually responds by pressing an OK button..
- Caution. Calls attention to an operation that may have undesirable results if it's allowed to continue. The user is given the choice to continue or not.
- Stop. Calls attention to a serious problem that requires that the user choose from alternative courses of action.

![](images/_page_65_Picture_6.jpeg)

Figure 23
Alert box icons

An application can define different responses for each of several stages of an alert, so that if the user persists in the same mistake, the application can issue increasingly helpful (or increasingly stern) messages. A typical sequence is for the first two consecutive occurrences of the mistake to result in a beep, and for subsequent occurrences to result in an alert box. This type of sequence is especially appropriate when the mistake is one that is probably accidental (for example, when the user chooses Cut when there's no text selection).

How the buttons in an alert box are labeled depends on the nature of the box. If the box presents the user with a situation in which no alternative actions are available, the box has a single button that's labeled OK. Clicking this button means "I've read the alert." If the user is given alternatives, then typically the alert is phrased as a question that can be answered "yes" or "no." In this case, buttons labeled Yes and No are appropriate, although variations such as Save and Don't Save are also acceptable. OK and Cancel can be used, as long as their meanings aren't ambiguous.

Generally, it's better to be polite than abrupt, even if it means lengthening the message. The role of the alert box is to be helpful and make constructive suggestions, not to give orders. But its focus is to help the user solve the problem, not to give an academic (no matter how interesting) description of the problem itself. It's important to phrase messages in alert boxes so that users aren't left guessing the real meaning.

Make alert messages self-explanatory. The user should never have to refer to a manual or reference card to find out what an alert message means. Test your alert messages to be sure they tell the user exactly what needs to be done.

The best way to make an alert message understandable is to think carefully through the error condition itself. Can the application handle this without an error? Is the error specific enough so that the user can fix the situation? What are the recommended solutions? Can the exact item causing the error be displayed in the alert message?