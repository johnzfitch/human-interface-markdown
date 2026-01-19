<!-- Chunk 204 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 314 -->
Mac OS X v10.5 and later provides images that represent the standard "user," "group," and "all" categories of permissions or privileges, including access control lists (or ACLs). Each of these images is shown in Table 11-6, along with its meaning and name. It is recommended that you use these images to clarify which users have permissions to read, write, or execute an item. These images allow you to avoid displaying Unix-style permissions indicators, such as rwxr-xrw-, which are suitable only for very sophisticated users.  
<span id="page-155-4"></span>Note that the "user group" permissions image shown in Table 11-6 looks similar to the image for the "user accounts" preferences category,shown in [Table](#page-154-1) 11-4 (page 155). As with allsystem-provided images, however, similar appearance does not imply similar meaning or usage. Be sure to avoid using system-provided images incorrectly.  
**Table 11-6** Images that represent categories of user permissions  
| Image | Permissions category | Constant name        |
|-------|----------------------|----------------------|
|       | User                 | NSImageNameUser      |
|       | A user group         | NSImageNameUserGroup |
|       | All users            | NSImageNameEveryone  |