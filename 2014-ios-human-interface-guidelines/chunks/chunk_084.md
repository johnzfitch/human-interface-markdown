<!-- Chunk 84 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 479 -->
- Spoken directions for every step of the journey
- A few feedback sounds
- The ability for users to continue to listen to their own audio  
In this app, the spoken navigation instructions represent the primary task, regardless of whether the app is in the background. For this reason, you'd use the Playback category, which allows your audio to play when the device is locked or switched to silent, and while the app is in the background.  
To allow people to listen to other audio while they use your app, you can add the kAudioSessionProperty\_OverrideCategoryMixWithOthers property. However, you also want to make sure that users can hear the spoken instructions above the audio they're currently playing. To do this, you can apply the kAudioSessionProperty\_OtherMixableAudioShouldDuck property to the audio session to ensuresthat your audio islouder than all currently playing audio, with the exception of phone audio on iPhone. These settings allow the app to reactivate its audio session while the app is in the background, which ensures  
#### **Scenario 5: A blogging app that allows users to upload their text and graphics to a website.** You provide:  
- A short startup sound file
- Variousshortsound effectsthat accompany user actions(such as a sound that plays when a post has been uploaded)
- An alert sound that plays when a posting fails  
that users get navigation updates in real time.  
In this app, sound enhances the user experience, but it's not essential. The main task has nothing to do with audio and users don't need to hear any sounds to successfully use the app. In this scenario, you'd use System Sound Services to produce sound. This is because the audio context of all sound in the app conforms to the intended purpose of this technology, which is to produce UI sound effects and alert sounds that obey device locking and the Ring/Silent (or Silent) switch in the way that users expect.