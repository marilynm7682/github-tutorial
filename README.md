# GitHub Tutorial

_by Marilyn Morales_

---
## Git vs. GitHub
   **What is Git?**  
  *  _Git is the version control._
  *  _Git runs in the command line._
  *  _takes a "snapshot", or a picture of your code._
   
   **What is Github?**
  *  _Github stores all the code in the cloud_
  *  _Github is aware of all the changes you make in your code._
  *  _Many people can work on the same files at once!_
  *  _[GitHub's Website](github.com)_
  
  **What is the difference between Git & GitHub?**  
* _Git does not require of Github but Github requires of Git_

---
## Initial Setup
##### Creating a GitHub account  
So how exactly do you create a GitHub account?  

    Here are the basic steps on how to create a GitHub account!:  
1.Start by opening Google Chrome, and opening a incognito page(optional)  
![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%206.40.14%20PM.png)  
2.Go to Github.com  
![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%207.20.29%20PM.png)  
3.Click on sign up  
4.Create a username and password for your account  
5.CONGRATULATIONS! Your Github account is good to go!  
    
##### Creating an SSH Key on Github  

    Here are the simple steps on how to create a SSH Key:  
   1. Open Google Chrome
   2. Go to the [website](Github.com)
   3. sign in and click on your profile icon at the top right  
   ![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%207.19.04%20PM.png) ![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%209.19.30%20PM.png)
   4. click on settings  
   ![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%209.19.40%20PM.png)
   5. On the left sidebar click on the SSH and GPG keys  
   ![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%209.45.18%20PM.png)
   6. Click on the new SSH key
   ![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%209.20.24%20PM.png)
   7. Give it an appropriate title  
   ![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%209.20.48%20PM.png)
   8. Now switch to cloud 9 and go to the right and click on on the gear icon to press SSH Keys   ![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%209.20.52%20PM.png)  
   9. Copy and paste the SSH keys  
   ![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%209.21.15%20PM.png)
   10. Press add SSH Key  
   ![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%209.21.02%20PM.png)  
   11. Open your workspace on Github and your good to go!

---
## Repository Setup

**What is a REPOSITORY?**
###### _A repo is basically a workspace where you have access to all the git commands you do, it stores all the files._
#### Making Your First Repo  
1. First type in ~cd/workspace  
2. Create a folder called and "first repo" or whatever you want to call it `mkdir` first-repo  
3. Now go on to the folder by typing `cd` first-repo  
4. Lastly Initialize it  
**What is git init?**
  `Git init` turns the folder that you created into a repository and when it initialzes it begins to save your files by taking "snapshots" of it. 
5. Now create a new file by typing `touch` readme.md  
6. You can open the file and type in something  
7. type in `git add` .  
**what is git add .?**
Git add, adds your file onto your repository  
8. Save your edits and give yourself a message of your edit by typing `git commit -m ""`  
** What is git commit?**
`Git commit` saves your file's changes. First you need to add something to the staging area and then you commit to save the final changes. 

#### Making your remote repo
1.Go on to Github.com  
2. on the top right click on the icon  
    ![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%2010.28.39%20PM.png)
3. Click on new repository  
4. Name your repository (ALWAYS NAME YOUR REPOSITORY THE SAME NAME YOU PUT FOR YOUR FOLDER)  
5. Create Repository  
6. Click on the SSH  
7. Copy each link one at a time an paste in onto your code   
    ![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%2010.32.47%20PM.png)
---
## Workflow & commands

**Here are some Git commands**  
    1. `Git status` - it is used to keep on track of all the changes you have made. We can use `git status` to see our edits
    If will either turn red or green.  
    2. `Git commit` - It is used to take a snapshot of your file. You can also use, 
    `Git commit -m ""` which means that it will save your files and at the same time you could give yourself a message of what were you editing. The messages come in handy. So like when you want to look back at your work you know exactly why you edited parts   
    3. `Git add` You could use git add when you want to save your file onto your repository but you have to commit it so that it could be in the version control.   
    4. `Git push` Pushes your edit and all the changes you made on your repository onto the cloud. 
    
## Error Handling
   What to do if you have errors? I mean everyone makes mistakes  
   Here are some errors that you might face  
   Error #1. 
![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%2010.59.41%20PM.png)  
What is the problem?  
_The person did not add the file to the staging area and so that's why it is not green._ 
   Solution to #1  
![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%2011.04.23%20PM.png)
What is the solution?  
_By typing Git add you now have added the file to the staging area therefore it is now green._

   Error #2  
![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%2011.04.23%20PM.png)
What is the problem?  
_The problem was that the person who wrote the code forgot to write a message when commiting so the computer did not understand what it was saying.
   Solution #2  
What is the solution?  
By pressing command q, it means that you quit the changes and then it would ask you if you want to save the files and you could say no by typing "N"

## Collaboration

How to fork and clone someone else's repository
    cloning a repository  
    _when you clone a repository you do not have access to push their remote but you do have access to a local repository_  
   Forking  a repository
   _when you fork someone elses repository you have a remote copy of their repository and you have access to push their remote_
   Let's get started:  
    1. Go to Github.com  
    2. Go to the person you want to clone and fork their repository  
    3. click on the fork icon  
![](https://preview.c9users.io/marilynm7682/github-learning/github-tutorial/Screen%20Shot%202016-10-24%20at%2011.27.01%20PM.png)  
    4. Now copy the SSH key and you're set you could now edit and push your work onto Github.  





