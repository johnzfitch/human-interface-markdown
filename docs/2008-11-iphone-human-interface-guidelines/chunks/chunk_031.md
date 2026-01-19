<!-- Chunk 31 | Source: 2008-11 iPhone Human Interface Guidelines.pdf | Est. Tokens: 4131 -->
Users expect greatsound from iPhone OS–based devices, whether they're hearing feedback sounds, ringtones, alert sounds, or application sounds, such as media playback, ambient sounds, or soundtracks. In addition, users expect sounds from their devices to obey both their preferences and their intentions.  
Users decide how loud sounds should be and whether they want to hear them at all. Sometimes, however, users expect to hearsounds even when their currentsettingsindicate that they prefersilence. Thisis because users want to hear sounds they ask for, but avoid hearing sounds they don't ask for.  
To help you accommodate this, iPhone OS provides programming interfaces you can use to:  
- Describe how your application's sounds should fit in with other sounds on the device
- Ensure that your application's sounds play according to users' expectations  
<span id="page-47-1"></span>Before you decide how to handle sound in your application, you need to understand how users expect applications and the device to behave when they adjust device controls and plug in and unplug headsets.  
#### The Ring/Silent Switch—What Users Expect  
Users use the Ring/Silent switch to silence their devices when they want to:  
- Avoid being interrupted by unexpected sounds, such as Phone ringtones and incoming Text message sounds.
- Avoid hearing soundsthat are the byproducts of user actions,such as keyboard or other feedback sounds, incidental sounds, or application startup sounds.
- Avoid hearing game sounds, including incidental sounds and soundtracks, that are not the primary purpose of the user's action.  
For example, in a theater users switch their devices to silent to avoid bothering other people in the theater. In this situation, users still want to be able to use applications on their devices, but they don't want to be surprised by sounds they don't expect or explicitly request, such as ringtones or new Text message sounds.  
However, the Ring/Silent switch does *not* silence sounds that result from user actions that are solely and explicitly intended to produce sound. For example:  
- Media playback in a media-only application is not silenced by the Ring/Silent switch because the media playback was explicitly requested by the user.
- A Clock alarm is not silenced by the Ring/Silent switch because the alarm was explicitly set by the user.
- A sound clip in a language-learning application is not silenced by the Ring/Silent switch because the user took explicit action to hear it.
- Conversation in an audio chat application is not silenced by the Ring/Silent switch because the user started such an application for the sole purpose of having an audio chat.  
This behavior follows the principle of user control because it is up to the user, not the device, to decide whether it's appropriate to hear sounds the user explicitly requests.  
#### <span id="page-48-0"></span>Volume Buttons—What Users Expect  
Users use the volume buttons to adjust the volume of all sounds their devices can play, including songs, application sounds, and device sounds. This means that users can always use the volume buttons to silence any sound, regardless of the position of the Ring/Silent switch.  
In some cases, it might be appropriate for an application to give users volume-setting capability in the application's user interface. For example, YouTube displays a slider control users can use to adjust the volume of the video they're watching. While YouTube is running, users can use the slider and the volume buttons interchangeably to affect the video's volume. Thisis because the slider acts as a proxy for the volume buttons while the application is running: It affects both the application's volume and overall system volume, with the exception of the ringer volume.  
Similarly, using the volume buttons to adjust an application's currently playing audio also adjusts the overall system volume, with the exception of the ringer volume. (Using the volume buttons when no audio is currently playing adjusts the ringer volume.)  
This behavior follows the principle of user control because the user always decides how loud sounds from their device should be.  
<span id="page-48-1"></span>Sometimes, an application might need to adjust relative, independent volume levels to produce the best mix in its audio output. But the volume of the final audio output should always follow the system volume, whether it's adjusted by the volume buttons or an application control. This means that control over the application's audio output remains in users' hands, where it belongs.  
#### Headsets and Headphones—What Users Expect  
Users plug in headsets and headphonesto hearsounds privately and to free their hands. Users have different expectations for application behavior, depending on whether they're plugging in or unplugging these accessories.  
When users plug in a headset or headphones, they intend to continue listening to the current audio, but privately. For this reason, they expect an application that is currently playing audio to continue playing without pause.  
<span id="page-48-2"></span>When users unplug a headset or headphones, they don't want to automatically share what they've been listening to with others. For this reason, they expect an application that is currently playing audio to pause, allowing them to explicitly restart playback when they're ready.  
#### Defining the Audio Behavior of Your Application  
If your application produces sound or performs recording, you need to decide how its audio behavior should fit in with the audio environment of the device. For most applications, this means accepting the standard interaction iPhone OS defines. This interaction, supported by System Sound Services, is well suited to applications that play only sounds that are incidental to application functionality, such as startup, feedback, or alertsounds. See "Using System Sound [Services"](#page-49-1) (page 50) for guidelines on when to use this programming interface.  
For applications that play or record audio as a primary part of application functionality or that play long soundtracks, the standard interaction might not be appropriate. When this is the case, you can declare a set of audio behaviors that can influence the way your application's audio fits in with the audio environment of the device. Audio Session Services supports the definition of audio behaviors (see "Using Audio [Session](#page-49-2) [Services"](#page-49-2) (page 50) for guidelines on when to use this programming interface).  
No matter what kind of audio your application produces or how you define its behavior, the phone can always interrupt the currently running application. This is because no application should prevent users from receiving an incoming call.  
#### <span id="page-49-1"></span>Using System Sound Services  
Use System Sound Services to play short sounds that are peripheral to the functionality of your application. Specifically, you should use System Sound Services if your application plays alert sounds only or sounds that:  
- Are 30 seconds or less in duration
- Do not need any level or positioning control
- Can always mix with other sounds played by the device
- Should always obey the Ring/Slient switch  
<span id="page-49-0"></span>Table 4-1 shows how short sounds played using the functions defined in System Sound Services respond to the Ring/Silent switch and mix with other sounds. (Sounds produced with either function obey the volume buttons.) For more information about System Sound Services, see "System Sound Services" in *Core Audio Overview*.  
**Table 4-1** System Sound Services functions you can use to play short, incidental sounds  
| Function                          | Obeys Ring/Silent<br>switch | Mixes with other<br>audio | Examples                                        |
|-----------------------------------|-----------------------------|---------------------------|-------------------------------------------------|
| AudioServicesPlay-<br>SystemSound | Yes                         | Yes                       | Tap feedback, short startup<br>sounds           |
| AudioServicesPlay-<br>AlertSound  | Yes                         | Yes                       | A failure alert or new message<br>arrival sound |  
**Note:** The AudioServicesPlayAlertSound function vibrates the device if, in Settings, Vibrate is on for alerts such as those produced by the arrival of a new Text message.  
<span id="page-49-2"></span>Be sure to use the AudioServicesPlayAlertSound function sparingly, and only when you're certain that users will appreciate being notified of the situation. To learn more about how you might use an alert in your application, see "Using [Alerts"](#page-69-0) (page 70).  
#### Using Audio Session Services  
Use Audio Session Services if you need to define a specific set of audio behaviors for your application. This can be the case if your application plays sounds that:  
Handling Common Tasks  
- Are a primary part of the application's functionality, such as audio in a media-playback application or sounds in a tone-matching game
- Are longer than 30 seconds, even if the sounds are not an essential part of application functionality
- Might need level or positioning control
- Should not mix with sounds from other applications  
Briefly, iPhone OS uses audio sessions to help determine how your application's audio should fit in with the audio environment of the device. Your application can use its audio session to declare a set of desired audio behaviors, including:  
- Whether your audio can mix with audio from other sources
- Whether your audio should play when the Ring/Silent switch is turned on  
Your application's audio session also provides notifications you can use to respond gracefully to interruptions and hardware audio route changes (such as the unplugging of a headset). For in-depth information on audio sessions, read *Audio Session Programming Guide*.  
To define a set of behaviors for your application's sounds, you specify an audio session *category*. iPhone OS provides seven categories, each of which encapsulates a set of behaviors. Specifying the proper category for the sounds in your application helps iPhone OS handle your sound appropriately and helps you deliver a better user experience.  
The vast majority of applications should use a single category to describe their audio behaviors. Only an application that uses audio in two very different ways, such as recording and playback, would have any need for more than one category.  
**Note:** For all applications, only one category is active at a time.  
An audio session governs sounds played using any of the following audio programming interfaces:  
- Audio Queue Services (see *Audio Queue Services Programming Guide*)
- OpenAL (see *OpenAL FAQ for iPhone OS*)
- I/O audio unit
- The AVAudioPlayer class (see *AVAudioPlayer Class Reference*)  
You can also use System Sound Services when you need to play short, incidental sounds. If you do this, be aware that your application's audio session does not in any way govern sounds played with System Sound Services. (See "Using System Sound [Services"](#page-49-1) (page 50) for guidelines on using this programming interface.)  
Table 4-2 lists the audio session categories and shows how each one responds to the Ring/Silent switch and whether it mixes with currently playing audio from othersources,such asiPod. (Keep in mind that all categories obey the volume buttons.)  
As you decide which category to choose, focus on whether the meaning of the category accurately describes your application's audio experience. If, instead, you focus only on a category's set of behaviors you're liable to disappoint user expectations. For example, choosing the media playback category for a game that plays a soundtrack meansthat users can't use the Ring/Silentswitch to play the game silently, asthey would expect.  
<span id="page-51-1"></span>**Table 4-2** Audio Session categories you can use to define sound behavior in your application  
| Category                       | Obeys<br>Ring/Silent<br>switch | Mixes with<br>other audio | Examples                                                                        |
|--------------------------------|--------------------------------|---------------------------|---------------------------------------------------------------------------------|
| UserInterface-<br>SoundEffects | Yes                            | Yes                       | Tap feedback, startup sounds                                                    |
| AmbientSound                   | Yes                            | Yes                       | Incidental sounds and noises                                                    |
| SoloAmbientSound               | Yes                            | No                        | A soundtrack in a game                                                          |
| MediaPlayback                  | No                             | No                        | Songs, videos, streaming audio                                                  |
| LiveAudio                      | No                             | No                        | Music or other real-time, user-created<br>sounds                                |
| RecordAudio                    | No                             | No                        | User-recorded audio                                                             |
| PlayAndRecord                  | No                             | No                        | Simultaneous audio input and output,<br>such as in a voice-changing application |  
<span id="page-51-0"></span>**Note:** If you don't declare an audio session category, your application is assigned to the solo ambient category by default.  
#### Putting it All Together  
Here are three scenarios that illustrate how you can take advantage of different sound services to provide an audio experience users appreciate.  
**Scenario 1**. Imagine that you're developing a blogging application that allows users to upload their text and graphics to a central website. You might have a short startup sound file, various short sound effects that accompany user actions (such as a sound file that plays when a post has been uploaded), and an alert sound that plays when a posting fails.  
In this application sound is incidental: The primary task has nothing to do with audio and users do not need to hear any sounds to successfully use the application. In this scenario, you should use the System Sound Services programming interfaces to play the sound files you create. These programming interfaces provide an easy way to play short sounds and ensure that these sounds obey the Ring/Silent switch the way users expect.  
**Scenario 2**. Imagine that you're developing an educational application that helps people learn a new language. You might have startup sounds that play when the application opens, feedback sounds that play when users tap specific controls, and recordings of words and phrases that play when users want to hear examples of correct pronunciation. To make sure these different sounds play the way users expect, you can:  
- Use System Sound Services when the application opens and when feedback sounds are playing.
- Assign the media playback category because the recorded words and phrases are primary functionality in your application.  
Handling Common Tasks  
When the Ring/Silent switch is set to silent, this allows your application to open without playing startup sounds and run without playing feedback sound effects, but play the educational content when users explicitly choose to hear it.  
**Scenario 3**. Imagine that you're developing a game that allows usersto guide an onscreen character through many different tasks. You might have startup sounds, gameplay sound effects, and a musical soundtrack. To make sure these different sounds play the way users expect, you can:  
- Use System Sound Services when the application opens.
- Assign the ambient solo category because the soundtrack and gameplay sound effects are important, but nonessential, parts of the application experience.  
When the Ring/Silent switch is set to silent, these choices allow users to play your game without hearing startup sounds, gameplay sounds, or the soundtrack. However, if a song in iPod is already playing when users start this game, the game soundtrack and gameplay sounds stop the iPod audio and play instead.