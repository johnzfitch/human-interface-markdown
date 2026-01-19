<!-- Chunk 57 | Source: 2006-10 Apple Human Interface Guidelines.pdf | Est. Tokens: 268 -->
<span id="page-48-6"></span><span id="page-48-4"></span>Writingsystems differin the direction inwhich their characters and lines flow, the size of the character set used, andwhether certain characters are context-dependent. Mac OS X supports Unicode, a single character set for mostwritingsystems in theworld. Unicode is a cross-platform, international standard for character encoding.  
Text handlingfor Cocoa is entirelybased on Unicode.For Carbon developers, there is a set of functions for manipulating Unicode text.For more information about Unicode support, see Internationalization Unicode Documentation.  
<span id="page-48-5"></span>No matter what level of worldwide text support you provide, it's important to keep in mind that:  
- <span id="page-48-3"></span>■ Text isn't always left-aligned and read from left to right.
- Text isn't always read by a person; it might be spoken through a screen reader.
- System and application fonts may change, so don't assume any particular font will be present. Instead, use the calls provided by your application framework.