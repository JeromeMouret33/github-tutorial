--------------------------------------------------------------------------------------------------------------------------------------------------
A simple tutorial for beginners (start from scratch on github)


1.Create account and repository 

	- Go to "https://github.com/" and create an account.
	- Click on "Create new repository".
	- Fill in the text area whith your project name "ex: MyProject".
	- Check "Public"
	- Click on "Create repository". 
	- For this example we will not check "initialize whith readme", you will do it for your next projects


2.Download, install and configure

	- Here you can downloald the lastest version of GitHub for MacOsX, Windows or Linux : "https://git-scm.com/downloads".
	- Download the compatible version for you system and install it.
	- On windows start GitBash ; For OsX and Linux just open a terminal.
	- type -> git config --global user.name "your name here".
	- type -> git config --global user.email "your email here".


3.Create your local repository
	
	- Create and go to the directory where you will store all your Github projects "ex : mkdir c:\users\myDirectory".
	- Create another directory with the name of your GitHub project and go there "ex : mkdir MyProject".
	- type -> git init 
	- This will tell your computer that this directory is a git directory.


4.Commit first file 

	- Create a "README.txt" in "MyProject" directory and write some text "ex : vim README.txt"
	- To check the presence of the file "README.txt" type -> git status 
	- "README.txt" will appear in red as an untracked file, this means that git ignores it for now.
	- To tell Git that the file is there, type -> git add README.txt
	- To take a "snapshot" of the project type -> git commit -m "your comment"

5.Connect your local repository to your GitHub repository and push

	- type -> git remote add origin https://github.com/nomutilisateur/MonProjet.git
	- To confirm type -> git remote -v
	- to push type -> git push -u origin master 