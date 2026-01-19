<!-- Chunk 78 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 722 -->
Mac OS X provides numerous technologies to help you perform secure operations. Using these technologies, you can store secret information locally, authorize a user for specific operations, or transport information securely across a network.  
<span id="page-78-11"></span>Consider the following guidelines when you need to work with sensitive information or work in a secure environment:  
- <span id="page-78-6"></span>■ Factor out code that requires privileged access into a separate process. Factoring isolates the secure code from the nonsecure code and makes it easier to verify that no rogue operations are occurring that could do damage, whether intentionally or unintentionally.
- <span id="page-78-9"></span>■ Avoid storing passwords and secrets in plain-text files. Even if you restrict access to the file using file permissions, the information is much safer in a keychain.
- <span id="page-78-8"></span>■ Avoid inventing your own authentication schemes. If you want a client-server operation to be secure, use the authorization APIs to guarantee the identity of the client.
- <span id="page-78-5"></span>■ Avoid loading plug-ins from privileged code. Plug-ins receive the same privileges as the parent process.
- <span id="page-78-4"></span><span id="page-78-3"></span>■ Avoid calling potentially dangerous functions, such as system or popen, from privileged code.
- Don't assume only one user is logged in. With fast user switching, multiple users may be active on the same system. See *Multiple User Environments* for more information.
- Don't assume that keychains are always stored as files.
- Avoid relying solely on passwords for authentication. Mac OS X already supports smart card devices. Biometric devices such as fingerprint scanners may also be available some day.  
Using Mac OS X Technologies  
<span id="page-79-5"></span><span id="page-79-3"></span>Ifyour application stores passwords or other sensitive information, such as credit card numbers, store that information using Keychain Services. Thekeychain mechanism in Mac OS X provides the following benefits:  
- <span id="page-79-4"></span>■ It provides a secure, predictable, consistent experience for users when dealing with passwords and other secret information.
- Users can modify settings for all of the passwords as a group or create separate keychains for different activities, with each keychain having its own activation settings. (By default, passwords are modified as a group.)
- The Keychain Access application provides a simple user interface for managing keychains and their settings, relieving you of this task.  
For information and links to security-related documentation in Mac OS X, see [Getting](http://developer.apple.com/referencelibrary/GettingStarted/GS_Security/index.html) Started With [Security](http://developer.apple.com/referencelibrary/GettingStarted/GS_Security/index.html).