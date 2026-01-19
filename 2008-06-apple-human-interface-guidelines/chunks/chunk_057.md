<!-- Chunk 57 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 263 -->
Writing systems differ in the direction in which their characters and lines flow, the size of the character set used, and whether certain characters are context-dependent. Mac OS X supports Unicode, a single character set for most writing systems in the world. Unicode is a cross-platform, international standard for character encoding.  
<span id="page-47-5"></span>Text handling for Cocoa is entirely based on Unicode. For Carbon developers, there is a set of functions for manipulating Unicode text. For more information about Unicode support,see *Internationalization Programming Topics*.  
<span id="page-47-3"></span>No matter what level of worldwide text support you provide, it's important to keep in mind that:  
- Text isn't always left-aligned and read from left to right.
- Text isn't always read by a person; it might be spoken through a screen reader.
- <span id="page-47-2"></span>■ System and application fonts may change, so don't assume any particular font will be present. Instead, use the calls provided by your application framework.