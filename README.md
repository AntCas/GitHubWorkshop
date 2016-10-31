Overview (60 minutes total)

00-05 introduction of the material
05-10 introduction of the first activity
10-20 activity #1 (10 minutes long)
20-25 go over what we just did
25-30 intoduce second activity
30-40 activity #2 (10 minutes long)
40-45 go over what we just did
45-47 introduce activity #3
47-57 go over what we just did
57-60 closing remarks


Run of Show (60 minutes total)

00-05 introduction of the material


	Intro Slide
		"Hello, welcome to the GitHub workshop, I hope you're all in the right place. My name is Anthony, and I'll be your guide today and this is Sam who will be helping me. I first learned git during my first internship. When I was interviewing for the position I thought I knew how to use git and I managed to convince the person who interviewed me, who happened to be the CEO, this was a very small 5-person startup, that I knew git. Then on the first day, they asked me to fetch their code, to make a pull request, and I realized I had no idea what was going on. So that afternoon I learned how to use git so I wouldn't lose my job. Since then I've used git all the time for class and for 3 other technical internships, and I've realized that even at a professional level, many people are still very uncomfortable with git. You definitely are not alone if you feel that git is complicated, that it has a steep learning curve. Most people don't really understand what is happening. Hopefully over the next hour we will get you to a place where you feel comfortable using the basics of git so it can be a useful tool to you in class and during hackathons instead of an the intimidating obstacle it often is."
	Short git intro
		"Before we get started, can anyone tell me what git it? Why do we use git?"
		<Take one or two answers, make sure to be encouring of even if not quite right>
		Very good, git is a version control system. It allows us to do two main things: 
			1) keep track of changes we make to code
				This is very useful when coding.
			2) collaborate with others
				Which is what we usually end up doing at hackathons

05-10 introduction of the first activity

	The first thing we are going to try then is tracking changes. The version control part of git. 
	First some vocab:
		repo (or repository): a directory or folder that contains a git project
		tracked file: a file git is watching for changes
		staging area: this is where you tell git what changes to record
		log: a history of all the versions of your project that you've saved with git
		commit: the act of saving a version of your project to git. A git commit is a snapshot of your project at a certain moment in time.

	Everyone should have their laptops out and a terminal window open. We are going to create a initialize a new git repo and make commit some changes. Follow along with the slide, if you get stuck ask your nighbor or one of us. We are on a schedule, so don't worry if you don't get all the way through. 

10-20 activity #1 (10 minutes long)

	<Do this part on the projector: (5 min with Sam helping people who get stuck)>
	make a new file called MyRepo
	In the terminal, navigate to MyRepo (cd MyRepo)
	~$ git init //initializes a new git project. If this is your first time using git it may ask you for your name and email at this point which you should enter.
	~$ echo "Happy Halloween" > spooky.txt
	~$ git status // explain the staging area
	~$ git add .
	~$ git commit -m "the message"
	~$ vim spooky.text // change the file
	// commit change to that file
	~$ git log // view and explain the log

	For the next 5 minutes try creating more files and changes and commiting those changes. Let us know if you are having any trouble. 
	<keep what you just did on the projector for people to copy><Set timer 5 minutes>

20-25 go over what we just did

		Alright, awesome. How did everyone do? Thumbs up if you were able to save a commit. Thumbs down if no. <Calibrate accordingly>

		Some of that might be confusing right now, and there's a good chance you won't retain all of it after this workshop, and that's OK! Just try and remember these concepts, and when you forget just ask someone nearby or search for it on Google. Asking questions is 99% of software engineering including git. You're measure of competence should not be how much you know, it should be how fast you can find the answer. And the fastest way to find the answer is usually by Googling it or just asking someone. You probably have found this out already in class and at your internships, and it works just the same with git.

	So what did we just do? 
		We created a new git project by using the ~$ git init command
		We created a file and saved the change to git using ~$ git add. and ~$ git commit -m
		We learned about the staging area which let's us see what changes we are recording

25-30 intoduce second activity

	Now we're going to learn about another very useful component of git, branching.

	More vocab:
		branch: alternate version of history.
		merge: combining different branches
		checkout: switching between different commits (which you'll remember is a snapshot of your code)

30-40 activity #2 (10 minutes long)

	<Do this part on the projector: (5 min with Sam helping people who get stuck)>
	~$ git checkout -b new_branch // create the new branch. In the future you will google "How to create a new branch in git"
	~$ git branch // view branches
	// make a change a commit it
	~$ git log
	~$ git checkout master // switch back to master
	// see that the file does not exist
	~$ git merge new_branch // gets the changes you made in your branch and merges them with master
	
40-45 go over what we just did

45-47 introduce activity #3

	Vocab:
		pull
		push
		pull request

	Now we're going to learn how to calaborate
	Open up your browser and go to github.com
	You should already have an account, if not create one now
	Click this '+' icon
	Name your repository
	follow instructions to upload the change
	make a change online
	pull the change
	make a new change
	push the change

47-57 go over what we just did

57-60 closing remarks
	

