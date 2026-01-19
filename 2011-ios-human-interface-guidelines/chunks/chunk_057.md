<!-- Chunk 57 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 394 -->
Although iOS apps can allow people to create and manipulate files, this does not mean that people should have an awareness of a file system on an iOS-based device.  
There is no iOS application analogous to the Mac OS X Finder, and people should not be asked to interact with files as they do on a computer. In particular, people should not be faced with anything that encourages them to think about file metadata or locations, such as:  
- An open or save dialog that exposes a file hierarchy
- Information about the permissions status of files  
If your application allows people to create and edit documents, it's appropriate to provide some sort of document picker that allowsthem to open an existing document or create a new one. Ideally,such a document picker:  
- **Is highly graphical**. People should be able to easily identify the document they want by looking at visual representations of the documents onscreen.
- **Allows people to make the fewest possible gestures to do whatthey want**. For example, people might scroll horizontally through a carousel of existing documents and open the desired one with a tap.
- **Includes a new document function**. Instead of making people go somewhere else to create a new document, a document picker can allow them to tap a placeholder image to create a new document.  
You can also use the Quick Look Preview feature to allow people to preview documents within your app, even if your app can't open them. To learn how to provide thisfeature in your app,see "Quick Look [Document](#page-78-0) [Preview"](#page-78-0) (page 79).