<!-- Chunk 44 | Source: 1982 Apple IIe Design Guidelines.pdf | Est. Tokens: 391 -->
(The following is a repeat of an earlier section. The keyword display is repeated here to make the document useful for reference.)  
In order to type a command or list selection without prompting, the user must learn what words he can type at any one point in the program. This learning problem can be overcome in a quite straightforward manner by displaying a list of all options then available. Typically, this can be done by creating a display similar to the standard menu format, with the center region devoted to the list of words:  
| Commodity Anal    | yser Belly Processes    | Pork Bellies |
|-------------------|-------------------------|--------------|
| Commands:         | Inventory Types:        |              |
| display           | complete l              | bellies      |
| graph             | partial belli           | ies          |
| compute           | dancing be              | ellies       |
| buy               |                         |              |
| sell              |                         |              |
| eat               |                         |              |
| delete            |                         |              |
| Type your instruc | ion and press RETURN: _ |              |  
Options: ESCAPE to leave OPEN-APPLE-? for help  
As the available options change, so do the options displayed. Thus, the user knows at every point exactly what she can select. (The display of command words could be made optional through the novice/expert flag; variable lists of words, such as file names, should always be visible.)