# HW3A Solution - Git and Version Control
## Part 1: Repository Cloning
I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to
`~/insy6500/class_repo`.
### Key Commands Used
- `git clone <url>` - Create local copy of remote repository
- `git log` - View commit history
- `git remote -v` - Check remote repository connections
## Part 2: Portfolio Repository Creation
I created my personal course repository with:
- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes
### Understanding Git Workflow
The three-stage workflow:
1. Working Directory: Where I edit files
2. Staging Area: Where I prepare commits with `git add`
3. Repository: Where commits are permanently stored with `git commit`
## Part 3: GitHub Publishing
Successfully published repository to GitHub:
- Used `git remote add origin` to connect local repo to GitHub
- Used `git push -u origin main` to upload commits
- Verified all files and commits are visible on GitHub
### The Remote Connection
My local repository is now connected to GitHub:
- `git remote -v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)
### Details
Complete this section with details from your setup:
- Repository URL: https://github.com/opc0002/py4eda-work.git
- Output of `git remote -v`:origin  https://github.com/opc0002/py4eda-work.git (fetch)
origin  https://github.com/opc0002/py4eda-work.git (push)
- The output of `git log --oneline`: 618f89e (HEAD -> main, origin/main) Add hw3a solution document
a1ecdea Inital commit: Add README and .gitignore
## Questions
### Reflection
#### Question 1
a) What I would typically make all my changes on a single file and if I wanted to make drastic changes I would make another file with a slightly different name. Compared to Git my method was very simple but it runs into the problem of always needing the file and I am not able to easily go back to previous versions. Git has the advantages of being able to pull from Git Hub and I can go back to old versions or see what comments I left about changes I made. 
b) I remember working on a large coding project in a group and it was difficutl to share the code and its supporting files. We used a google doc to past all the code into and if someone needed to update it, they would have to copy the code and paste it in. Git would allow us upload the code file to Git Hub and Git's commit history would allow each group member to be able see what changes have been made. This would save us time trying to figure out who made what changes and when they were made.
#### Question 2
a) It is important to keep things seperated because one repo is read only and one is my own work. If they were not seperated it would could create file name conflicts between the read only files and my work. There is also the problem of accessing Git Hub. I don't think it would work well to pull from one and push to a different one.
b) I will probably sperate my repos into three main categories. One will be my projects and research, which will contain mostly private material. The second one will be for work and projects. This will have a mix of private, public, and read only repositories and will make sharing work much easier. The last repository will be primarily for read only repositories and maybe other files that need to be stored.
#### Question 3
a) The second commit message is more useful, because it tells what is actually being made and or changed whole the first gives limited information and does not give anything to go back to. I may need to find this commit in the future when I am trying to remember the documentation of Git workflow and repository structure and the first commit would not help me at all to find it.
b) I believe I would make a commit when I would add a feature, fixed bugs, or I need to work on it later and I want a backup that I can access anywhere. I think a good "unit of work" are things that transform the code or allow acces at another location. 
### Graduate Questions
#### Question 1
a) If I commit all the files at once, I lose access to a version that has just the readme file and the .gitignore. I would also lose the ability to seperate those inital values. 
b) I would commit now for the write code to load data and update to your readme. Those I think are impactful. The fix a typo in a comment I would wait to commit because I think it is too minor to by itself and I think it isn't impact to wait. The start working on a new analysis function (half-finished) depends on some factors. If I am working in a group, I may upload the half finished code so that the group can work on it. I may also commit it, if I am stepping away and want to make a backup just in case. Staging helps with decision making because it can show how many things are going to be pushed and may incline to push when a lot of changes are being made.
c) Git Status helps with decisions about what to stage and commit because it allows to see what different and can highlight what is in the repository. It should be used when switching between what is being worked on or coming back to a repository.
#### Question 2
a) I believe that "distributed" version control system means that users are able to push and pull when they want to and go back to previous version. Google Drive and Dropbox update whenever a change is made. 
b) This is valuable because it means that internet connect is always needed to work in a repository and can allow for more flexible workflows. It also enables working from different enviroments.
c) Git clone makes a copy of a repository. Git pull connects to Git Hub and updates hardware with the online files while git push uploads changes to Git Hub. I can only use Git pull on the class_repo because I have not been given access to make changes so I can only update my files. I can do push and pull on my repo because I have permission to do so.
#### Question 3
a) I plan to consider if the commit will impact the repository in a meaningful way to me. This could be uploading a incomplete large code that I have stopped working on at the momenet or several bug fixes or typo corrections. I think I will balance my commits by considering what is needed at the time and I think transform the product meaningfully.
b) I think a porfolio README is more personal and could give specific instructions the maker has made while the open source README may be generic and probably lengthy. The portfolio README may give better insight into the repository.
c) Habits I should develop now with this portfolio are making good commits with good comments and establishing a proper structure to the portfolio. These will be valuable later because it will allow me to easily find what I have worked on in the past, what changes I made, and it will set me up for success when I have to do these in the future. I can also point back to this portfolio to show some of the work I have done.

