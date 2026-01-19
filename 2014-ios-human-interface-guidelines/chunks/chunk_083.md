<!-- Chunk 83 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 492 -->
- The ability to accept audio input
- The ability to play audio  
In this app, sound is essential to the primary functionality. People use this app to communicate with others, often while they're currently using a different app. Users expect to be able to receive calls when they've switched their device to silent or the device is locked, and they expect other audio to be silent for the duration of a call. They also expect to be able to continue calls when the app is in the background.  
To produce the expected user experience for this app, you'd use the Play and Record category, and you'd be sure to activate your audio session only when you need it so that users can use other audio between calls.  
#### **Scenario 3: A game that allows users to guide a character through different tasks.** You provide:  
- Various gameplay sound effects
- A musical soundtrack  
In this app, sound greatly enhances the user experience, but isn't essential to the main task. Also, users are likely to appreciate being able to play the game silently or while listening to songsin their music library instead of to the game soundtrack.  
The best strategy is to find out if users are listening to other audio when your app starts. Don't ask users to choose whether they want to listen to other audio or listen to your soundtrack. Instead, use the Audio Session Services function AudioSessionGetProperty to query the state of the  
kAudioSessionProperty\_OtherAudioIsPlaying property. Based on the answer to this query, you can choose either the Ambient or Solo Ambient categories (both categories allow users to play the game silently):  
- If users are listening to other audio, you should assume that they'd like to continue listening and wouldn't appreciate being forced to listen to the game soundtrack instead. In this situation, you'd choose the Ambient category.
- If users aren't listening to any other audio when your app starts, you'd choose the Solo Ambient category.