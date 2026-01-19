<!-- Chunk 90 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 1219 -->
Sometimes, currently playing audio is interrupted by audio from a different app. For example, an incoming phone call interruptsthe current iPhone app's audio for the duration of the call. In a multitasking environment, the frequency of such audio interruptions can be great.  
To provide an audio experience users appreciate, iOS relies on you to:  
- Identify the type of audio interruption your app can cause
- Respond appropriately when your app continues after an audio interruption ends  
Every application needs to identify the type of audio interruption it can cause, but not every application needs to determine how to respond to the end of an audio interruption. This is because, for most types of apps, the appropriate response to the end of an audio interruption is to resume playing audio. Only apps that are primarily or partly media playback apps, and that provide media playback controls, have to take an extra step to determine the appropriate response.  
Conceptually, there are two types of audio interruptions, based on the type of audio that is doing the interrupting and the way users expect the particular app to respond when the interruption ends:  
● Resumable interruption. A resumable interruption is caused by audio that users view as a temporary interlude in their primary listening experience.  
After a resumable interruption ends, an app that displays controls for media playback should resume what it was doing when the interruption occurred, whether this is playing audio or remaining paused. An app that doesn't have media playback controls should resume playing audio.  
For example, consider a user listening to an app for music playback on iPhone when a VoIP call arrives in the middle of a song. The user answers the call, expecting the playback app to be silent while they talk. After the call ends, the user expects the playback app to automatically resume playing the song, because the music—not the call—constitutestheir primary listening experience *and* they had not paused the music before the call arrived. If, on the other hand, the user had paused music playback before the call arrived, they would expect the music to remain paused after the call ends.  
Other examples of appsthat can cause resumable interruptions are appsthat play alarms, audio prompts (such as spoken driving directions), or other intermittent audio.  
● Nonresumable interruption. A nonresumable interruption is caused by audio that users view as a primary listening experience, such as audio from a media playback app.  
After a nonresumable interruption ends, an app that displays media playback controlsshould not resume playing audio. An app that doesn't have media playback controls should resume playing audio.  
For example, consider a user listening to a music playback application (music app 1) when a different music playback application (music app 2) interrupts. In response, the user decides to listen to music app 2 for some period of time. After quitting music app 2, the user would not expect music app 1 to automatically resume playing because they'd deliberately made music app 2 their primary listening experience.  
The following guidelines help you decide what information to supply and how to continue after an audio interruption ends.  
**Identify the type of audio interruption your app caused**. You do this by deactivating your audio session in one of the following two ways when your audio is finished:  
- If your app caused a resumable interruption, deactivate your audio session with the AVAudioSessionSetActiveFlags\_NotifyOthersOnDeactivation flag.
- If your app caused a nonresumable interruption, deactivate your audio session without any flags.  
Providing, or not providing, the flags allows iOS to give interrupted apps the ability to resume playing their audio automatically, if appropriate.  
**Determine whether you should resume audio when an audio interruption ends**. You base this decision on the audio user experience you provide in your app.  
● If your app displays media playback controls that people use to play or pause audio, you need to check the AVAudioSessionInterruptionFlags\_ShouldResume flag when an audio interruption ends.  
If your app receives the Should Resume flag, you should have your app:  
- Resume playing audio if your app was actively playing audio when it was interrupted
- Not resume playing audio if your app was *not* actively playing audio when it was interrupted
- If your app does not display any media playback controls that people can use to play or pause audio, you should have your app always resume previously playing audio when an audio interruption ends. You do not have to check for the presence of the Should Resume flag.  
<span id="page-85-0"></span>For example, a game that plays a soundtrack should automatically resume playing the soundtrack after an interruption.