<!-- Chunk 27 | Source: 2008-11 iPhone Human Interface Guidelines.pdf | Est. Tokens: 324 -->
iPhone applicationsshould start instantly so users can begin using them without delay. When starting, iPhone applications should:  
- Specify the appropriate status barstyle (see "The [Status](#page-60-1) Bar" (page 61) for information about the available styles).
- Display a launch image that closely resembles the first screen of the application. This decreases the perceived launch time of your application. For more information, see ["Launch](#page-112-0) Images" (page 113).
- Avoid displaying an About window, a splash screen, or providing any other type of startup experience that prevents people from using your application immediately.
- By default, launch in portrait orientation. If you intend your application to be used only in landscape orientation, launch in landscape and allow usersto rotate the device to landscape orientation if necessary.
- A landscape-only application should support both landscape orientations—that is, with the Home button on the right or on the left. If the device is already physically in a landscape orientation, a landscape-only application should launch in that orientation. Otherwise, a landscape-only application should launch in the orientation with the Home button on the right by default.
- Restore state from the last time your application ran.