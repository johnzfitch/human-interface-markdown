<!-- Chunk 80 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 280 -->
<span id="page-63-7"></span>The Mac OS X application bundling scheme is designed to support localized strings, images, nib files, and other resources. However, there is more to designing an application for use in different markets than just including the right translated strings. "Worldwide [Compatibility"](#page-46-1) (page 47) provides some general design considerations for building internationalization into your application.  
<span id="page-63-6"></span>At a minimum, your internationalization checklist should include the following items:  
- Implement your program as a bundle so that you can take advantage of the built-in internationalization support for bundles.
- Support Unicode text. Mac OS X provides full support for Unicode, and so should your application.
- Modify your code to get user-visible strings from .strings files. Use Core Foundation and Cocoa interfaces to load strings from resource files in your bundle.
- Use nib files to store your user interface data.  
For further guidelines and information about how to internationalize your applications,see *Internationalization Programming Topics*.