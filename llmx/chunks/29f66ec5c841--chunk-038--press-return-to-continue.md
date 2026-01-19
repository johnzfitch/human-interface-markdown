---
chunk_index: 150
ref: "29f66ec5c841"
id: "29f66ec5c841260b525c1df5e88a8a06f581c363ff1188535deab96c61f192aa"
slug: "chunk-038--press-return-to-continue"
path: "marker/1982 Apple IIe Design Guidelines/chunks/chunk_038.md"
kind: "markdown"
lines: [48, 58]
token_estimate: 668
content_sha256: "cb3b9f0625baa63be1e4b5ad4ccd2b26447a3f55d1a7f87722c974c734fc2b0f"
compacted: false
heading_path: ["\"Press RETURN to continue\""]
symbol: null
address: null
asset_path: null
---

#### "Press RETURN to continue"  
The user can control the movement from one display to the next by pressing the RETURN key (or, optionally but consistently, SPACE bar). He is informed by a message such as, "Press the RETURN key to go on to the menu." on the bottom line of the screen. (Delay loops are difficult to judge as to the proper duration, and become somewhat insulting to the intelligence of the user.) The actual prompt message should give some indication as to what will happen next, rather than simply saying "Press RETURN to continue."  
The educational software community has pretty much selected SPACE bar instead of RETURN to control movement: children were found to occasionally press RESET by accident on the older Apple II's and Apple II Plusses. Please be consistent in your choice of RETURN or SPACE bar, not only within a given program, but across your complete product line.  
Do not tell the user to "press any key." On the Apple II series computers, you cannot read every key by itself: RESET, SHIFT, CONTROL. We have also found in testing that new users, in particular, panic when asked to press any key. Over 80% of them will turn around and say, "but what key should I press?" In questioning them about this response, we discovered that they are quite convinced that even though the prompt implied all keys were OK to press, some could be dangerous. Of course, they were quite right.  
While you should not tell them to press any key, you may, in this specific case only, accept more than the key specified. Both RETURN and SPACE bar should be accepted, even though only one is prompted for: users grow used to using one or the other. You may optionally (and only in this specific case of using the key as a switch) want to accept most keys, so that a user striking out for SPACE bar and pressing V by accident will not be penalized. Do not accept ESCAPE instead of RETURN or SPACE bar.  
Displays with several input statements:  
- Movement from input to input is sequential: the user may move back and forth but not randomly skip around.
- Pressing the RETURN key automatically positions the user at the next input statement.
- Pressing CTRL-B automatically positions the user at the previous input statement. The prior response to the previous input will be displayed as that input's default.
- The last input on the display will normally ask if the user has completed all responses to her satisfaction.
- No input will be accepted without the user explicitly terminating it, usually with RETURN or CTRL-B. The fact that the user has used up all the spaces available in the field should not automatically move the user to the next question.