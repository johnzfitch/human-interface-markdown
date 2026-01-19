<!-- Chunk 44 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 261 -->
Writingsystems differin the direction inwhich their characters and lines flow, the size of the character set used, andwhether certain characters are context-dependent. Mac OS X supports Unicode, a single character set for mostwritingsystems in theworld. Unicode is a cross-platform, international standard for character encoding.  
<span id="page-39-5"></span>Text handlingfor Cocoa is entirelybased on Unicode.For Carbon developers, there is a set of functions for manipulating Unicode text.For more information about Unicode support, see Internationalization Unicode Documentation.  
<span id="page-39-3"></span>No matter what level of worldwide text support you provide, it's important to keep in mind that:  
- Text isn't always left-aligned and read from left to right.
- Text isn't always read by a person; it might be spoken through a screen reader.
- <span id="page-39-2"></span>■ System and application fonts may change, so don't assume any particular font will be present. Instead, use the calls provided by your application framework.