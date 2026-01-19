<!-- Chunk 281 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 397 -->
It's important to distinguish between the speech engine and the applications that call the engine. The Mac OS X speech-recognition engine  
- is speaker independent. Users don't have to invest any time training it to recognize their voice before they can use it.
- supports continuous speech. Users don't have to pause between words.
- has a large vocabulary (more than 120,000 words) and linguistic analysis to predict the correct pronunciation of words not in its dictionary.
- works with "far-field" microphones, so users don't have to tether themselves to the computer with a headset. In addition, most Macintosh computers have a built-in microphone. All microphones in Macintosh computers are optimized to work well with the Mac OS X speech-recognition engine.
- works with a finite-state grammar. This is the most successful general-purpose speech technology and is optimal for uses such as interactive dialogs, command-and-control, and language/literacy. It is not optimal, however, for unrestricted dictation.  
In order to have the most flexibility in using speech recognition, an application should call the speech engine functions directly. Doing so requires the following steps:  
- 1. Tell the engine what to listen for (that is, define what users can say).
- 2. Start listening.
- 3. Act on the message sent to the application when the engine hears a defined command.  
Alternatively, you can easily provide basic speech control of your application by taking advantage of Apple's Speakable Items application (see ["Speakable Items"](#page-254-2) [\(page 255\)\)](#page-254-2).