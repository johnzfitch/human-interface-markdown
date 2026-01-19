<!-- Chunk 64 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 281 -->
<span id="page-63-5"></span>The Mac OS X application bundling scheme is designed to support localized strings, images, nib files, and other resources. However, there is more to designing an application for use in different markets than just including the right translated strings. "Worldwide [Compatibility"](#page-46-1) (page 47) provides some general design considerations for building internationalization into your application.  
At a minimum, your internationalization checklist should include the following items:  
● Implement your program as a bundle so that you can take advantage of the built-in internationalization support for bundles.  
The Mac OS X Environment  
- Support Unicode text. Mac OS X provides full support for Unicode, and so should your application.
- Modify your code to get user-visible strings from .strings files. Use Core Foundation and Cocoa interfaces to load strings from resource files in your bundle.
- Use nib files to store your user interface data.  
For further guidelines and information about how to internationalize your applications,see *Internationalization Programming Topics*.