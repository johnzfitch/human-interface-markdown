<!-- Chunk 43 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 1454 -->
Most things—menu items, icons, buttons, and so forth—should highlight by reversing the white background with the colored or black bits when selected. (For example, if the item is red on a white background, it should highlight to white on <sup>a</sup> red background.) However, if multiple colors of text appear together, Color TextEdit allows the user to set the highlighting bar color to something other than black to highlight the text better. The default for the bar color is always black.  
#### Menus  
In general, the only use of color in menus should be in menus used to choose colors. However, color could also be useful for directing the user's choices in training and tutorial materials: one color can lead the user through a lesson.  
#### Windows  
Since the focus of attention is on the content region of the window, color should be used only in that area. Using color in the scroll bars or title bar can simply distract the user. (The one exception is that if the user has color-coded icons in the Finder, the title of <sup>a</sup> window—not the whole title bar—may be the same color as the icon from which it came.)  
#### Dialog and alert boxes  
Except for dialog boxes used to select colors, there's no reason to color the controls or text in dialog boxes; they should be designed and laid out clearly enough that color isn't necessary to separate different sections or items. Alert boxes must be as clear as possible; color can add confusion instead of clarity. For example, if you tried to make things clearer by using red to mean dangerous and green to mean safe in the Erase Disk alert box, the OK button—"go"—would be red and the Cancel button—"stop"—would be green. Don't do this.  
#### <sup>I</sup> Pointers  
The pointer should always be visible. Most of the time, when it's being used for selecting and choosing, it should remain black—color might not be visible over potentially different colored backgrounds, and wouldn't give the user any extra information. However, when the user is drawing or typing in color, the drawing or text-insertion pointer should appear in the color that is being used. Except for [multicolored paintbrush pointers, the pointer shouldn't contain more than one color lat once—it's hard for the eye to discriminate small areas of color.  
#### Sound  
The high-quality sound capabilities of some Apple computers let sound be integrated into the human interface to give users additional information. This section refers to sound as a part of the interface in standard applications, not to the way sound is used in an application that uses the sound itself as data, such as a music composition application.  
#### When to use sound  
There are two general ways that sound can be used in the interface:  
- ☐ It can be **integrated** throughout the standard interface to help make the user aware of the state of the computer or application.
- ☐ It can be used to **alert** the user when something happens unexpectedly, in the background, or behind the user's back.  
In general, when you would like to put an indicator on the screen to tell the user that something has occurred—for example, that mail has come in, or that a particular process has finished—this is a good time to use a sound.  
#### **Getting attention**  
If the computer is doing something time-consuming, and the user may have turned away from the screen, sound is a good way to let the user know that the process is finished, or it needs attention. (There should also be an indication on the screen, of course.)  
#### **Alerts**  
Common alerts can use sounds other than the SysBeep for their first stage or two before bringing up an alert box. For example, when the user tries to paste when there's nothing in the Clipboard, or tries to backspace past the top of a field, different sounds could alert them.  
#### Modes  
If your application has different states or modes, each one can have a particular sound when it is entered or exited. This can emphasize the current mode, and prevent confusion.  
#### General guidelines  
Although the use of sound in the Desktop Interface hasn't been investigated thoroughly, these are some general guidelines to keep in mind.  
#### Restraint  
Be thoughtful about where and how you use sound in an application. If you overuse sound, it won't add any meaning to the interface, and will probably just be annoying.  
#### Redundancy  
Sound should never be the only indication that something has happened; there should always be a visible indication on the screen, too, especially when the user needs to know what has occurred. The user may have all sound turned off, may have been out of hearing range of the computer, or may be hard of hearing.  
#### Unobtrusiveness  
Most sounds can be quite subtle and still getting their meaning across. Loud, harsh sounds can be offensive or intimidating. You should always use the sound yourself and test it on users for a significant period of time (a week or two, not twenty minutes) before including it in your application—if you turn it off after a day, chances are other people will, too. You should also avoid using tunes or jingles—more than two or three notes of a tune may become annoying or sound silly if heard very often.  
#### Significant differences  
Users can learn to recognize and discriminate between sounds, but different sounds should be significantly different. Nonmusicians often can't tell the difference between two similar notes or chords, especially when they're separated by a space of time.  
#### User control  
The user can change the volume of sounds, or turn sound off altogether, using the Control Panel desk accessory. You should remember this, and should never override this capability. Always store sounds as resources, so users can change sounds and add additional sounds.