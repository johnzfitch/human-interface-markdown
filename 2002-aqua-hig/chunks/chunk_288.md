<!-- Chunk 288 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 588 -->
As much as possible, you should observe the following guidelines when designing your application to support TTS.  
- Use speech synthesis to notify the user of something that happened in the background, such as, "Your download is finished" or "You have a meeting in 15 minutes."
- When using speech synthesis to notify users that an event has occurred, consider pausing for a few seconds between the visual display of the event—such as a sheet—and the spoken message. Speech is an effective way to get users' attention only if they are not already looking at the screen, and the delay gives users the opportunity to respond to the notification without hearing any speech. If such a pause is appropriate, provide a way for users to customize its length.
- Provide a way for users to turn TTS on or off within your application and to control such things as volume, voice, and speaking rate.
- Information users enter, such as typing in text fields or selections from long lists, should be spoken back by the computer. For example, if a user types an amount of money, it's helpful to speak it back immediately to confirm it. Similarly, sometimes users select the wrong item from a list; speech synthesis is a good way to bring this mistake to the user's attention.
- Speak in response to spoken commands to confirm what was recognized and what action is being performed. For example:  
*User:* Disconnect from the Internet. *Computer:* Disconnecting now.  
*User:* Schedule a meeting. *Computer:* For what time?  
- When testing your application, test with speech on and be sure to listen to all spoken text in your interface. You can override the default TTS of a control by providing an alternative text string.
- Make spoken text sound best by breaking up long sentences and using punctuation effectively, and by using embedded speech commands such as [[emph+]] to focus users' attention on important information. For technical information, see the Apple developer documentation website.
- Make sure your alerts are well-written and clear. (See ["Writing Good Alert](#page-231-1)  [Messages" \(page 232\)](#page-231-1).) Avoid long sentences and awkward phrasing.
- In applications that make use of characters (human or otherwise) or running commentary, such as games, consider using text-to-speech instead of digitizing voices.  
Speech Synthesis **259**