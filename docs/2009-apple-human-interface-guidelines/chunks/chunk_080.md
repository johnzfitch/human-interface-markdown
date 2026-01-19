<!-- Chunk 80 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 700 -->
Mac OS X provides numeroustechnologiesto help you perform secure operations. Using these technologies, you can store secret information locally, authorize a user for specific operations, or transport information securely across a network.  
<span id="page-75-11"></span>Consider the following guidelines when you need to work with sensitive information or work in a secure environment:  
- <span id="page-75-6"></span>● Factor out code that requires privileged access into a separate process. Factoring isolates the secure code from the nonsecure code and makes it easier to verify that no rogue operations are occurring that could do damage, whether intentionally or unintentionally.
- <span id="page-75-9"></span>● Avoid storing passwords and secrets in plain-text files. Even if you restrict access to the file using file permissions, the information is much safer in a keychain.
- <span id="page-75-8"></span>● Avoid inventing your own authentication schemes. If you want a client-server operation to be secure, use the authorization APIs to guarantee the identity of the client.
- Avoid loading plug-ins from privileged code. Plug-ins receive the same privileges as the parent process.
- <span id="page-75-5"></span><span id="page-75-3"></span>● Avoid calling potentially dangerous functions, such as system or popen, from privileged code.
- <span id="page-75-4"></span>● Don't assume only one user is logged in. With fast user switching, multiple users may be active on the same system. See *Multiple User Environments* for more information.
- Don't assume that keychains are always stored as files.
- Avoid relying solely on passwords for authentication. Mac OS X already supports smart card devices. Biometric devices such as fingerprint scanners may also be available some day.  
Using Mac OS X Technologies  
<span id="page-76-3"></span><span id="page-76-1"></span>If your application stores passwords or other sensitive information, such as credit card numbers, store that information using Keychain Services. The keychain mechanism in Mac OS X provides the following benefits:  
- It provides a secure, predictable, consistent experience for users when dealing with passwords and other secret information.
- <span id="page-76-2"></span>● Users can modify settings for all of the passwords as a group or create separate keychains for different activities, with each keychain having its own activation settings. (By default, passwords are modified as a group.)
- The Keychain Access application provides a simple user interface for managing keychains and their settings, relieving you of this task.  
For information and links to security-related documentation in Mac OS X, see Getting Started With [Security.](http://developer.apple.com/referencelibrary/GettingStarted/GS_Security/index.html)