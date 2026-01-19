---
chunk_index: 788
ref: "56f063131af2"
id: "56f063131af29f399e5ac616d237e882c8ddbe7b1e1a9bcf23abee83f1495b6c"
slug: "chunk-070--alerts"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_070.md"
kind: "markdown"
lines: [43, 61]
token_estimate: 1000
content_sha256: "19408de5b96dc8a76a81520bcd9e4851bceeb64e93c2cdf08758ecd91b9cd3e8"
compacted: false
heading_path: ["Buttons","Check Boxes and Radio Buttons","Dials","Alerts"]
symbol: null
address: null
asset_path: null
---

#### Alerts  
Every user of every application is liable to do something that the application won't understand or can't cope with in a normal manner. Alerts give applications a way to respond to errors not only in a consistent manner, but in stages according to the severity of the error, the user's level of expertise, and the particular history of the error. The two kinds of alerts are beeps and alert boxes.  
Beeps are used for errors that are both minor and immediately obvious. For example, if the user tries to backspace past the left boundary of a text field, the application could beep instead of displaying an alert box.  
An alert box looks like a modal dialog box, except that it's somewhat narrower and appears lower on the screen. An alert box is primarily a one-way communication from the system to the user. The only way the user can respond is by clicking buttons or by pressing Enter or Return. Alert boxes, therefore, might contain dials and buttons but usually not text fields, radio buttons, or check boxes.  
![](images/_page_92_Picture_3.jpeg)  
Figure 48. A Typical Alert Box  
There are three types of alert boxes:  
- Note. A minor mistake that wouldn't have any disastrous consequences if left as is.
- Caution. An operation that may or may not have undesirable results if it's allowed to continue. The user is given the choice whether or not to continue.
- Stop. A serious problem or other situation that requires remedial action by the user.  
An application can define different responses for each of several stages of an alert, so that if the user persists in the same mistake, the application can issue increasingly helpful (or sterner) messages. A typical sequence is for the first two occurrences of the mistake to result in a beep, and for subsequent occurrences to result in an alert box. This type of sequence is especially appropriate when the mistake is one that has a high probability of being accidental (for example, when the user chooses Cut when there's no text selection).  
How the buttons in an alert box are labeled depends on the nature of the box. If the box presents the user with a situation in which no alternative actions are available, the box has a single button that's labeled OK. Clicking this button means "I've read the alert." If the user is given alternatives, then typically the alert is phrased as a question that can be answered "yes" or "no." In this case, buttons labeled Yes and No are appropriate, although variations such as Save and Don't Save are also acceptable. OK and Cancel can be used, as long as their meanings aren't ambiguous.  
The default button is boldly outlined and takes effect if the user presses Return or Enter.  
Use icons whenever possible. Graphics can better describe some error situations than words, and familiar icons help users better distinguish between alternatives. Icons should contain no words, and they should contain no symbols unique to a particular culture.  
Generally, it's better to be polite than abrupt, even if it means lengthening the message. The role of the alert box is to be helpful and make constructive suggestions, not to give orders. But its focus is to help the user solve the problem, not to give an academic (no  
matter how interesting) description of the problem itself. It's important to phrase messages in alert boxes so that users aren't left guessing the real meaning. Avoid computer jargon.  
Make alert messages self-explanatory. The user should never have to refer to a book or reference card to fmd out what an alert message means. Test your alert messages to be sure they tell the user exactly what needs to be done.  
The best way to make an alert message understandable is to think carefully through the error condition itself. Can the application handle this without an error? Is the error specific enough so that the user can fix the situation? What are the recommended solutions? Can the exact item causing the error be displayed in the alert message?  
*i'*(