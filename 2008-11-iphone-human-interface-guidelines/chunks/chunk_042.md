<!-- Chunk 42 | Source: 2008-11 iPhone Human Interface Guidelines.pdf | Est. Tokens: 824 -->
If your application provides different perspectives on the same set of data, or different subtasks related to the overall function of the application, you might want to use a tab bar. A tab bar appears at the bottom edge of the screen.  
A tab bar gives usersthe ability to switch among different modes or viewsin an application, and usersshould be able to access these modes from everywhere in the application. However, a tab bar should never be used as a toolbar, which contains buttons that act on elements in the current mode (see ["Toolbars"](#page-63-0) (page 64) for more information on toolbars).  
For example, on iPhone, iPod uses a tab bar to allow users to choose which part of their media collection to focus on, such as Podcasts, artists, videos, or playlists. The Clock application, on the other hand, uses a tab bar to give users access to the four functions of the application, namely, World Clock, Alarm, Stopwatch, and Timer. Figure 6-9 shows how selecting a tab in a tab bar changes the view in Clock. Notice how the tab bar remains visible in the different Clock modes shown in Figure 6-9. This makes it easy for users to see which mode they're in, and allows them to access all Clock modes regardless of the current mode.  
<span id="page-65-0"></span>**Figure 6-9** A tab bar switches views in an application  
![](images/_page_65_Figure_5.jpeg)  
![](images/_page_65_Figure_6.jpeg)  
<span id="page-65-1"></span>The tab bar displays icons and text in tabs, each of which are equal in width and display a black background. Because it's recommended that the hit-region of a user interface element be 44 x 44 pixels, it's a good idea to display five or fewer tabs in a tab bar; otherwise, it can be difficult for users to tap a specific one. When a tab is selected, its background lightens and the image in the tab is highlighted. Figure 6-10 shows how this looks.  
**Figure 6-10** A selected tab in a tab bar  
![](images/_page_65_Picture_9.jpeg)  
You can display a badge on a tab to communicate with users in a nonintrusive, understated way. This type of feedback is suitable for communicating information that isn't critical to the user's task or context, but that is useful to know. The badge looks similar to the one Phone displays on the Voicemail tab to indicate the number of unheard messages: it is a red oval with white text inside that's near the upper right corner of the Navigation Bars, Tab Bars, Toolbars, and the Status Bar  
tab. Associating a badge with a specific tab allows you to connect the information in the badge with a particular mode in your application. (Note that your application cannot display a badge on your application icon in the Home screen, because third-party iPhone applications do not run in the background.)  
<span id="page-66-0"></span>Figure 6-11 shows an example of a badge on a tab.  
**Figure 6-11** A badge conveys information in a tab bar  
![](images/_page_66_Picture_5.jpeg)  
iPhone OS provides a number of icons you can use in your tabs, such as the items labeled Favorites and Recents in Figure 6-11. For more information on the tab bar icons available to you, see ["Standard](#page-107-0) Icons for Use in Tab [Bars"](#page-107-0) (page 108).  
#### **CHAPTER 6**  
Navigation Bars, Tab Bars, Toolbars, and the Status Bar