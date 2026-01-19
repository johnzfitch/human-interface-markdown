<!-- Chunk 62 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 287 -->
<span id="page-65-7"></span><span id="page-65-6"></span>The Mac OS X application bundlingscheme is designed to support localized strings, images, nib files, and other resources. However, there is more to designing an application for use in different markets than just including the right translated strings. "Worldwide [Compatibility"](#page-49-0) (page 50) provides some general design considerations for building internationalization into your application.  
At a minimum, your internationalization checklist should include the following items:  
- Implement your program as a bundle so that you can take advantage of the built-in internationalization support for bundles.
- Support Unicode text. Mac OS X provides full support for Unicode, and so should your application.
- Modifyyour code toget user-visible strings from .strings files. Use CoreFoundation and Cocoa interfaces to load strings from resource files in your bundle.
- Use nib files to store your user interface data.  
<span id="page-65-4"></span>For further guidelines and information about how to internationalize your applications, see *Internationalization Programming Topics*.