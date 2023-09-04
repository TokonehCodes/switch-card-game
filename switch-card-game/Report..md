Primarily, I used 2 main methods to find the errors in the code.
The first was the built in Issue Tracker in PyCharm. 
It was very helpful in pointing out the “obvious” errors that could’ve easily been 
overlooked if I were going through the code line by line. 
For example, The error on line 50 in the players file with the open bracket. 
This file wasn’t too long, so it might not have been too difficult to spot, 
however the issue tracker was helpful nonetheless. 
One function in it which I found especially useful was the colour coding of the errors.
It sort of represented the priority/importance of each error. 
This not only came in handy for fixing the issue that prevented the code from working, 
but also for finding things to reduce code smell/make the code look more pythonic.
One of the code smell issues that the colour coding pointed out for me was the length of the notes 
which I corrected in the switch file – which showed up as a gray coloured error.

Aside from the Issue Tracker, the main method I used to find the errors was the testing. 
The tests were very helpful to find issues which may not have shown up as errors in the issue tracker, 
but caused the code not to work as it should have.
A small, simple issue that this helped me find was the defining that Ace and Queen can be played at any time, 
defining the function with a False as oppose to a True. 
I simply searched the function in used in the test (‘can_discard’) in the switch file and found where the issue was. 
The ability to search in python also made the debugging job a lot easier. 
I did, however, still check the tests themselves thoroughly, which is how I found that 
the adhere_to_pick4 test was wrong, which used values of K as oppose to Q.

After finding what the issue was I primarily used the comments and READ.ME to find out why they’re wrong.
To be more specific, they helped me find out what each function was actually supposed to do.
This was possibly the most useful of all, because you can’t check many issues using print statements 
due to the nature of the program. 
Making helpful notes is such a useful part of coding and definitely something I will implement in my own coding. 
I also just corrected error messages in the terminal after I ran the code. 
These messages were quite detailed as they showed where exactly the error is.

I improved the code by:
-	fixing some indentation inaccuracies (line 198 switch)
-	reducing the character count on a single line (111 switch file)
-	Placing a comment on a new line (68 switch file)
-	Importing correctly (UI in both players and switch files)
