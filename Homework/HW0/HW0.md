# Homework 0 Getting Started

In this assignment gives you will set up your account for using github to keep up with class activities, and you will read up on the materials we will cover in lectures 1 and 2. The sooner you do these, the better you will be prepared for class.

You will maintain two remote repositories: 

- one for class information such as homework assignments and materials (called *Class_Resources*) This is a public repo, meaning *anyone in the world can see it*, but only I and Andrew can change it.

- one for private communications with me (which will have the same name as your git id). This is **only accessible to you, me, and Andrew**.

## Due **Thursday 8/23**

0. Sign up for a github account, if you don’t already have one, at: https://github.com

	a. Email me (foster@uidaho.edu) your github id. Without this, you can't submit homework, and I can't grade it.

1. Create directory for the course. 

	a. Using bash, create ~/CompSkills_F18

	(Optional) I recommend creating ~/CompSkills_F18/Notes and ~/CompSkills_F18/Sandbox. These are directories where you can keep your own notes, and a place to just try things out. These would not be on git, unless you put them there.
	
2. Clone the online course information repository onto your computer

	a. log into github.com with your git id
	
	b. Search (box at top left) for jamesafoster repo named Class_Resources, jump to that repo
	
	c. Clone (green button on right) into your ~/CompSkills_F18 directory. This will ask you where to put the clone. Put it in ~/CompSkills_F18. This creates a *local* version of the Class_Resources repo in your course directory. 
	
	Is is **very important** to remember that there are now two copies of the course information repo: one online (which only Andrew and I can change) and one on your computer. Sync your local copy **frequently** (with the "Sync" button on upper right. Otherwise, you may miss out on important course information (such as changes to the homework, or new assignments). It is your responsibility to keep up to date.

3. Clone your (private) online homework directory onto your machine.

	a. I will create a private repository with the same name as your github ID (from step 0). I will add you as a "collaborator" to this repo, so that you can submit homework and other stuff, and receive feedback. You and I will share read/write access to this repository. Note: **I cannot set up your homework repo until you send me your github ID**. 

	b. I will email you information about this private repo. 
	
	c. Clone this repo onto your machine into the ~/CompSkills_F18 directory (as in step 2). You will turn in homework here, and Andrew and I will return grades, comments, and other confidential information here. 
		
	e. Make the your local version of the private repo (which will be ~/CompSkills_F18/*yourGitID*, where *yourGitID* is your git ID). From the terminal, enter this command (exactly! that is an "ell" after the hyphen.):
		
		ls -lR ~/CompSkills_F18 > ./HW0
		
	**NOTE:** This step is how I will grade this homework assignment.

## Prepare for class by **Tuesday 8/28 (class 3)**

0. Work through unix tutorial: http://www.ee.surrey.ac.uk/Teaching/Unix/ except for Chapters 7 and 8 

1. Work through https://guides.github.com, GitHub Flow, Hello World, and Forking Projects

2. Work through the github markdown tutorial: https://guides.github.com/features/mastering-markdown/ 
