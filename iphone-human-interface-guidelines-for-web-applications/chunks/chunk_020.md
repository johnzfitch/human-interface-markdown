<!-- Chunk 20 | Source: iPhone Human Interface Guidelines for Web Applications.pdf | Est. Tokens: 506 -->
Responsiveness means that an iPhone web application or webpage is perceived to respond quickly and accurately to users' requests and gestures. Responsiveness in an iPhone web application or webpage is even more important than it is in an application or webpage on the desktop, because users are constantly aware of the passage of time, both in terms of the flow of real-world events and in the usage of the battery.  
As described in "Network [Connectivity"](#page-9-2) (page 10), you can't predict what network speed users experience at any given time, because iPhone automatically switches to the currently available network. As a general rule, therefore, you should design your solution so that it loads quickly and works well at the slowest connection speed. In addition, be sure to provide adequate feedback on potentially lengthy processes (as described in ["Communication"](#page-25-0) (page 26)) so that users know your content is still responding.  
If your webpage or iPhone web application seems unresponsive, users may not give it a second chance. Here are some things you can do to increase perceived performance:  
- Optimize images.
- Be mindful of the recommended limits on image sizes (for specifics on these limits, see Creating Compatible Web Content) and supply reduced-size images whenever possible.
- Consider using JavaScript to draw elements,such as controls and backgrounds, instead of adding existing images to your resources.
- Handle video and audio content correctly.
- iPhone streams movies and audio using HTTP over EDGE and Wi-Fi networks. See Creating Video for details on how to ensure a great audio and video experience on iPhone.
- Make sure JavaScript execution does not exceed 5 seconds for each top-level entry point. Execution longer than 5 seconds raises an exception and makes your webpage seem unresponsive.
- Be mindful of resource limits.
- Make sure your webpage or application does not contain unneeded JavaScript, which consumes memory resources without providing any benefit.