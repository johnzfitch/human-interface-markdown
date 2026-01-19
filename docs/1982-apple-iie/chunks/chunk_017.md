<!-- Chunk 17 | Source: 1982 Apple IIe Design Guidelines.pdf | Est. Tokens: 2147 -->
Once the users have been profiled and a prototype built, it is time to begin testing.  
Human interfaces are not made; they evolve. Software designers are simply too close to their product, their computer, and have put up with the most abysmal interfaces themselves for too many years to be able to outguess the naive user. Products must be repeatedly tested on "real people". ("Real people" means the target audience: as soon as you find yourself sitting in a meeting with other computerists, all announcing what users will or will not feel/think/do, you are in trouble. Build the prototype and find out.)  
The job of the designer is to do her best to predict the response of the user; the job of the user is to do just the opposite.  
Human interface testing is quite different from the kind of exhaustive "boundary condition" testing used to uncover bugs. You should begin testing as early as possible, using drafted friends, relatives, and new employees, to uncover the really big holes in your design. As you get closer to a finished product, try it out on larger groups drawn from the target population.  
It is imperative that the designers actually watch people use the program. Do not just send off copies of the program and expect written responses. Get the users and the designers in a quiet room together.  
Our testing method is as follows. We set up a room with five to six computer systems. We schedule two to three groups of five to six users at a time to try out the systems (often without their knowing that it is the software rather than the system that we are testing). We have two of the designers in the room. Any fewer, and they miss a lot of what is going on. Any more and the users feel as though there is always someone breathing down their necks.  
The initial ground rules are that no questions will be answered, as by the time the formal testing begins, we can supply a draft of the manual. (Usually by the second group, some glaring defects in the interface have shown up, and we have to give them help getting past the stumbling blocks.)  
Ninety-five percent of the stumbling blocks are found by watching the body language of the users. Watch for squinting eyes, hunched shoulders, shaking heads, and deep, heart-felt sighs. When a user hits a snag, he will assume it is "on account of he is not too bright": he will not report it; he will hide it. Make notes of each problem and where it occurred. Question the users at the end of the session to explore why the problems occurred. Do not make assumptions about why a user became confused. Ask him. You will often be surprised to learn what the user thought the program was doing at the time he got lost.  
We have found that prepared questionnaires handed out at the end of a session are of little value: you will seldom predict the problem areas before testing, and users will lie to spare everyone's feelings. (If you had figured out the problem areas, you would have already fixed them.)  
Generally, two or three groups on one occasion is more than sufficient: patterns will emerge almost immediately. You should have at least one more bank of testing after any major revision; as the next example shows, one often jumps out of the frying pan, into the fire.  
#### The True Anecdote:  
Herein follows a true anecdote that illustrates how difficult the most simple human interface issue can be, and why thorough testing on real people is so important. (If you dislike true anecdotes, please skip ahead to "Goals.")  
As we tune in, the authors of APPLE PRESENTS...APPLE, both of whom pride themselves on clever interface design, have anguished for hours over difficult passages in their program. It was to turn out their guesses were quite accurate in said difficult passages. It was the simplest question of all that caused all the problems...  
Problem: in APPLE PRESENTS...APPLE, an Introduction to  
the Apple IIe Computer, the training program for teaching fundamentals of using the new Apple IIe computer, find out if the user is working with a color  
monitor.  
User profiles: new owner, customer in a computer store, or  
member of a class learning to use Apple  
computers.  
Test user  
profiles:  
customers in a computer store, non-computerists in a classroom environment, friends, and relatives.  
First design:  
Prompt:  
A color graphic would be displayed.  
"Are you using a color TV on the Apple?"  
Anticipated  
problem:  
Those who were using a monochrome monitor in a classroom or computer store situation wouldn't know whether the monitor was black and white or  
was color with the color turned off.  
First attempt:  
Prompt:  
A color graphic was displayed. "Is the picture above in color?"  
Failure rate: 25%  
Reason:  
As anticipated, but incorrectly overcome, those seeing black and white thought their color might be turned down. They didn't answer the question wrong; they turned around and asked one of the authors whether the monitor in question was color or not. A decision was made that the authors could  
not be shipped with each disk.  
Second attempt: A smaller graphic with large-letter words in their  
own vivid colors was substituted:  
GREEN BLUE ORANGE MAGENTA  
Prompt: "Are the words above in color?"  
Failure rate: color TV users: none  
black and white monitor users: none green-screen monitor users: 100%  
Third attempt: The graphic remained the same.  
Prompt: "Are the words above in more than one color?"  
Failure rate: color TV users: none  
black and white monitor users: 20% green-screen monitor users: 50%  
Reasons: the black and white monitor users who answered  
incorrectly admitted that they did so on purpose. (Our methods for wringing their confessions shall remain proprietary.) 50% of the green-screen folk considered that they were looking at both black and green — two colors — and answered the guestion  
accordingly.  
Fourth attempt: Same display of graphic and colored text  
Prompt: "Are the words above in several different colors?"  
Failure rate: color TV users: none  
black and white monitor users: 20% green-screen monitor users: 25%  
Reasons: By this time, the authors were prepared to supply  
everyone who bought an Apple with a free color monitor, just so we would not have to ask the question. It turns out that around 20% of the people were not really reading the question. They were  
responding to:  
"Are the words above, several different colors?"  
Fifth attempt: Same display of graphic and colored text  
Prompt: "Do the words above appear in several different  
colors?"  
001010  
Failure rate: none.  
In case it appears the authors were simply dull fellows, be it known that this was a fully-interactive training program in excess of 100K, and this was the only interface issue that required more than one correction. It clearly exemplifies how even the most careful designers can totally miss when guessing at how users are going to respond.  
Had the designers not tested the program, it is probable that dealers would not have used the program in their showrooms, as they would have wearied of telling potential customers that they were/were not using a color TV and that the APPLE PRESENTS... APPLE program was being very stupid to ask the question like that. (Potential customers, of course, wouldn't have fallen for such an explanation: they would have known it was the computer that asked the question, and everyone knows that one should always buy the computer that asks good questions.)  
It is vital that programs and manuals be tested early and often with users from the target audience; this testing should be an integral part of any testing plan. This testing seems like a lot of extra effort, but in practice, it really isn't, beyond the mechanical difficulties of getting your equipment and test group together. (Computer stores, colleges, and shopping centers are often good random-testing locations.) The above testing cycles took only four days: the first two days were on-site, using new Apple employees. Only two days of testing required any set-up work at all, and the overall improvement to the product was clearly worth the effort.  
Even if the interface had not changed at all, it would have been worth it just to be able to ward off all the self-proclaimed experts with their (day-after-going-to-production) comments of "Boy, I sure wouldn't have done it that way. A lot of people out there are gonna have trouble." What joy to turn to such people and announce with a clear conscience, "Well, we tried it out on 109 people, and they all sailed through with flying colors."