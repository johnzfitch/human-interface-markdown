<!-- Chunk 98 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 322 -->
Ordinary panels-those that aren't attention panels-look and act very much like standard windows. They're typically in the same tier as standard windows, so they compete with them for screen space. They have title bars just like standard windows, although panels don't usually have miniaturize buttons. However, ordinary panels differ from windows in a number of ways:  
- They can never be the main window.
- They shouldn't become the key window unless they accept characters from the keyboard.
- They generally aren't visible unless they belong to the active application-they rarely persist on-screen once the application has been deactivated.  
In addition, some ordinary panels are in a tier above standard windows, as discussed later in "Floating Panels."  
#### **Programming Note: Creating Panels**  
The Application Kit contains several ready-made ordinary and attention panels that you can use, as well as functions that let you easily create basic attention panels. You can also create custom panels-either ordinary panels or more complex attention panels. If you create a custom attention panel, you are responsible for making sure that the panel looks like an attention panel. (Similarly, custom ordinary panels should look like ordinary panels, and not like attention panels.)