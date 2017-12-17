# How-to-Crack-PDP
This repo is meant to help all students help students in Programming Design Paradims (PDP)

If you're a master's northeastern student, you know the pain.

Skip over to section [Solution](#Solution).

# Problems:

1.Time consuming to write boiler-plate code and/or comments

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;PDP is good when it comes to learning a functional language and learning how to designing scalable,modular and readble programs.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Having said that heavy emphasis is given to boiler-plate/comments which is a good thing,since the codebase one would work on would be shared by multiple peers,and one must write code which is readable and debugable by others,I understand that it's time consuming, Can we get the best of both worlds ? Yes :) 

2.The use of Dr-Racket as an IDE

2.1: Code looks the following before submission

![alt text][beforeSubmission]

# <a name="After Submission"></a>2.2 Code After submission

![alt text][afterSubmission]

2.3 No Syntax Coloring

![alt text][nosyntaxHighlihting]

2.4 With Syntax Coloring

![alt text][nosyntaxHighlihting]

2.4 Lack of autocomplete

![alt text][nosyntaxHighlihting]

2.5 Forgetting to commit/push the commited code for evalution :sob:

2.6 Manual filling of work-log after work-session,which i guess can be automated.

2.7 Slower to compile and at times produces cryptic error messages.

# <a name="Solution"></a>Solution

Use emacs or spacemacs (incase you're a vim user like me)

Native emacs/spacemacs doesn't support racket out of the box.

We have to install racket mode on top of emacs/spacemacs to take support emacs/spacemacs.

With Racket mode we have 

2.1 Syntax Coloring

![alt text][withsyntaxHighlihting]

2.2 Autocomplete

![alt text][autoComplete]

2.3 Snippets for Boilerplate code.

2.4 Auto Commit Plugin for those who forget to commit/push the latest code.

2.5 Automatic filling of work log after every work session

2.6 Faster Compilation and better error messages.

2.7 No changes to code after submission 

![alt text][afterSubmission]

The reason why the code changes after submission is because students often practise racket with images file embedded into the source code

The DrRacket encodes the images into a specific format hence when someone tries to open the source code in anything other than DrRacket

We have a gibberish code and since Github doesn't use DrRacket when we open the code,We have the issue mentioned.

Now since emacs/spacemacs does'nt support image encoding we would not have the problem faced otherwise.

[beforeSubmission]: https://github.com/aravind-kumar/How-to-Crack-PDP/blob/master/images/no%20syntax%20coloring.png

[afterSubmission]:  https://github.com/aravind-kumar/How-to-Crack-PDP/blob/master/images/after%20submission.png

[autoComplete]: https://github.com/aravind-kumar/How-to-Crack-PDP/blob/master/images/Autocomplete_new.png

[nosyntaxHighlihting]: https://github.com/aravind-kumar/How-to-Crack-PDP/blob/master/images/no%20syntax%20coloring.png
 
[withsyntaxHighlihting]: https://github.com/aravind-kumar/How-to-Crack-PDP/blob/master/images/syntax%20coloring.png
 



