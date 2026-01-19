<!-- Chunk 81 | Source: 2006-10 Apple Human Interface Guidelines.pdf | Est. Tokens: 635 -->
With Automator, a user can automate common procedures and buildworkflows byarranging processes from different applications into a desired order. Familiar Apple applications, such as Mail, iPhoto, and Safari make their tasks available to users to organize into a workflow. These tasks (called *actions*) are simple and narrowly defined, such as opening a file or applying a filter, so a user can include them in different workflows.  
As an application developer, you can define actions that represent discrete tasks your application can perform. You make these actions available to users by creating action plug-ins that implement the appropriate behavior. An action plug-in contains a nib file and some code to manage the action's user interface and implement its behavior. You can develop action plug-ins using either AppleScript or Objective-C. You might consider creating a set of basic actions to ship with your application so users have a starting point for using your application with Automator.  
<span id="page-61-2"></span>For more information on developing Automator actions, see *Automator Programming Guide*.  
As you design the user interface of an action, keep the following guidelines in mind:  
- Users stack actions on top of each other in Automator. Because display screens are wider than they are tall, you should minimize the use of vertical space. One way to do this is to use a pop-up menu instead of radio buttons, even if there are only two choices.
- Don't use group boxes. An action does not need to separate or group controls with a group box.
- Avoid tab views. Instead, use hidden tab views to alternate between different sets of controls.
- Avoid usinglabels to repeat the action's title or description; these take up spacewithout providing value.
- Use a disclosure triangle to hide and display optional settings. (See ["Disclosure](#page-271-1) Triangles" (page 272) for more information on disclosure triangles.)  
Using Mac OS X Technologies  
- Use small Aqua controls to minimize the use of space. (In ["Controls"](#page-230-0) (page 231), you can find information on the dimensions of those controls that are available in the small size.)
- Use 10-pixel margins to make the best use of the space.
- Provide feedback. Use the appropriate progress indicator when an action needs time to complete (see "Progress [Indicators"](#page-260-0) (page 261) for more information on these controls).
- If possible, display an example showing the effect of the action so users can see the impact of various settings.