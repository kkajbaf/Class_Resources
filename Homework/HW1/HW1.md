# Homework 1, Practice with Bash

In this assignment gives you will practice bash commands and redirection

**Assigned:** 30 August

**Due:** 6 September (Class 6)

## Remember

Remember, you can look at the markdown code for these homework assignments as examples of markdown formatting.

See the *Class_Preparation* folder for how to prepare for classes.

## Practice Unix Commands and bash scripting

For this assignment, you will use *cp*, *ls*, *mkdir*, redirection (*\>* and *\>\>*), pipe (|) *echo*, *grep*, *wc*, and *tail*. 
You will also use the usual *git* mechanisms to finalize your homework (via commit), and to submit it (via sync).

0. Use a *working_on_it* branch in your private homework repo

1. Create a *HW1* directory in the private repo for your homework (should be named *_\<your_git_id\>*).

2. Add an appropriate README.md to this directory

3. Create a file named *bash_practice.txt* in this directory with these steps:

	a. Use *echo* and redirection to add the text “*\<yourName\>*, Homework 1”

	b. Add the full file information (using *ls -l*) about ~/CompSkills\_F16/Homework/Resources. (or whatever you called the directory in the class repo that contains stuff related to homework.)

	c. Add the text “Number of sequences: “

	d. Use *grep* and *wc* to output the number of fasta records in *~/CompSkills\_F18/Homework/Resources/HW1-sequences.fsa* (remember, fasta records begin with ‘>’)

	e. Add the last 12 lines of *~/CompSkills_F18/Homework/Resources/HW1-sequences.fsa* (using *tail*)

## Turn in homework

0. Commit your work

1. When you're happy with your work, switch to the master branch.

2. Update your local master branch from your working branch.

3. Sync with the remote master. This is how we will turn in homework! Note that we will NOT check the working branch!

## Grading

We will grade your homework by checking script-output.txt for accuracy. 

grade | if
----- | :---------
0     | you don't turn in anything (in the *master* branch of *HW1* in your private repo)
1     | you turn in something but it isn't correct
2     | you turn in something, some is correct but some isn't
3     | All of your code is correct, but it violates proper style, or has poor/missing comments
4     | what you turned in is correct, stylish, and complete
