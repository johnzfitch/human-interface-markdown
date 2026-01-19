<!-- Chunk 197 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 312 -->
OS X provides images that represent the standard "user," "group," and "all" categories of permissions or privileges, including access control lists (or ACLs). Each of these images is shown in Table 74-6, along with its meaning and name. It's recommended that you use these images to clarify which users have permissions to read, write, or execute an item. These images allow you to avoid displaying Unix-style permissions indicators, such as rwxr-xrw-, which are suitable only for very sophisticated users.  
<span id="page-335-1"></span>Note that the "user group" permissions image shown in Table 74-6 looks similar to the image for the "user accounts" preferences category, shown in [Table](#page-334-0) 74-4 (page 335). As with all system-provided images, however, similar appearance does not imply similar meaning or usage. Always use system-provided images according to their semantic meaning.  
**Table 74-6** Images that represent categories of user permissions  
| Image | Permissions category | Constant name        |
|-------|----------------------|----------------------|
|       | User                 | NSImageNameUser      |
|       | A<br>user<br>group   | NSImageNameUserGroup |
|       | All<br>users         | NSImageNameEveryone  |