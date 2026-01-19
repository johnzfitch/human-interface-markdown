<!-- Chunk 150 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 508 -->
People can choose an Action extension in a few different ways. Specifically, people can:  
- Open the Share menu and choose the extension
- Click the extension's toolbar button
- Hold the pointer over selected content or an attachment, click the button that appears, and choose the extension in the menu (shown here in TextEdit)  
![](images/_page_239_Picture_7.jpeg)  
There are two types of Action extensions:  
● **Viewer.** A viewer Action extension displays the current content in a custom way, but doesn't modify it.  
● **Editor.** An editor Action extension can let users edit the current content. After users confirm their edits, the extension replaces the original content in the host app with the edited version. The system-provided Markup extension is an example of an editor Action extension.  
**Note:** In the Share and contextual menus, OS X lists only the Action extensions that can work with the current content type. For example, when the user's current content is a video, OS X doesn't list Action extensions that support only text.  
**If appropriate, display your Action extension UI within the context ofthe host app.** For example, the built-in Markup action extension letsthe user edit the image without leaving the primary app (shown here in TextEdit).  
![](images/_page_240_Picture_4.jpeg)  
**Use a monochromatic version of the app icon for an Action extension.** (In contrast, a Share extension uses its containing app's full-color app icon.) To create an icon for an Action extension, you might start by creating a stencil version of your app icon. If necessary, simplify the design by focusing on the elements that make your icon unique.  
If you provide multiple Action extensions in your containing app, it can work well to create a family of icons for them. Be sure to make every icon in the family look related to the containing app's icon.  
**Note:** You can also register an Action extension as a toolbar item, which means that host apps can display your monochromatic Action icon in the toolbar.