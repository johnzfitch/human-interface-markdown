---
chunk_index: 152
ref: "fae8be6d7f32"
id: "fae8be6d7f32dd0040e5b459e4e52579bef9a4563dedb040f0688148288fc0fa"
slug: "chunk-038--error-trapping"
path: "marker/1982 Apple IIe Design Guidelines/chunks/chunk_038.md"
kind: "markdown"
lines: [60, 70]
token_estimate: 837
content_sha256: "0a2000e84dc2b53a875102a85f9121ae933f3acb5303c881374f9aecec951b05"
compacted: false
heading_path: ["\"Press RETURN to continue\"","Errors","**Error Trapping**"]
symbol: null
address: null
asset_path: null
---

#### **Error Trapping**  
In most situations, user inputs must be checked for validity. Account numbers, employee numbers, and dates are just a few examples of items that should be checked to see if the data requested is on file or plausible. Numeric inputs should be screened for values too small or too large, if extreme values are invalid or potentially damaging to the program. An error message line should be provided in a consistent location toward the bottom of the display.  
Many types of errors can be circumvented through software design: If, in testing, you find users repeatedly making the same kind of errors, change the software.  
Make your program insensitive to upper/lower case when no distinction is necessary. Be particularly aware on Apple II programs: the new Apple IIe can generate lower-case characters. (Make sure you only  
transform characters: many of those obscure punctuation marks are often-used special characters on foreign keyboards.)  
Spaces should never be significant. Users look upon a space as a lack of a character, not as a character. Strip leading and trailing spaces, and intervening spaces too, when practical. For example, when prompting the user for the name of an existing file, should the user respond "door bell", first look for a literal match, then strip spaces, so that you can match with the user's original, but now forgotten, "doorbell".  
Likewise, do not refer to "the RETURN character", unless you are prepared to deliver an essay. Users steadfastly cling to their belief that RETURN is an action, not a character.  
Do not make commands position-dependent. For example, do not set up a stream of "parameters" such that if the user wishes to change the fourth parameter, she must type three commas to signify acceptance of the first three "default" parameters. If the meaning of the above sentence is not immediately clear, you have gotten the point.  
When a menu offers a set of choices, or the user is otherwise prompted to respond to a restricted set of options, then the program should recognize only the responses that are valid. Do not offer the user a menu of options, most of which cannot be used. If the user needs to select a file before deciding to Edit, Save, or Delete, let him know. Don't make him go down through a list, getting the same unenlightening message, "Option not currently valid."  
Enable only those keys you have informed the user you are enabling. Do not prompt: "Press ESCAPE to end, RETURN to continue..." and fail to announce that SPACE bar will eliminate this afternoon's files. The classic negative example of this is an early Apple text editor with a verified replace option. According to the manual (no instructions were displayed), R meant replace this occurrence, SPACE bar signified do not replace this occurrence. The actual code was such that any character with an ASCII value of 82 (R) or above caused a replacement, and any character with an ASCII value less than 82 caused a skip. Therefore, "[" would replace, "8" would not, "^" would replace, "," would not. Confusion yet reigns over that one.  
Having presented the rule, here is the exception: when using SPACE bar or RETURN as a switch ("Press RETURN to continue") you may want to accept all reasonable keys surrounding the intended target, so as to not penalize the user for poor aim.