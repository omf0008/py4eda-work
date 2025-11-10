# HW3A Solution- Git and Version Control
## Part 1: Repository Cloning
I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to `~/insy6500/class_repo`.

## Key Commands Used
- `git clone <url>`- Create local copy of remote repository
- `git log`- View commit history
- `git remote-v`- Check remote repository connections

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
- Used `git push-u origin main` to upload commits
- Verified all files and commits are visible on GitHub

### The Remote Connection

My local repository is now connected to GitHub:
- `git remote-v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)
 
### Details
Complete this section with details from your setup:
- Repository URL: https://github.com/omf0008/py4eda-work
- Output of `git remote-v`: 
	origin  https://github.com/omf0008/py4eda-work.git (fetch)
	origin  https://github.com/omf0008/py4eda-work.git (push)
- The output of `git log--oneline`: 
	0579449 (HEAD -> main, origin/main) Add hw3a solution document
	1073f4d Initial commit: Add README and .gitignore

## Questions

### Reflections:

1
- Before this assignment, how did you typically manage different versions of your work (e.g.,
 assignments, code, documents)? Compare that approach to using Git. What are 2-3 specific
 advantages Git provides?
	- Before now I have created folders "manually" and placed files all in the same folder. With Git I would be able to access all folders and documents in a consistent manner that gives me more control. Git is more organized and consistent.
- Describe a situation from your academic or professional work where Git’s commit history
 would have been valuable. What problem would it have solved?
	- Recently I have an assignment to write a script that read csv files, organized the data, and run a heuristic. The csv files I used were copies from an Excel file that was given. What was turned in was a report, the code, csv files, and the original Excel file that was edited for another part of the assignment.
	- Being able to put all of the files in a repository through Git and creating an `.md` file to walk through the code would have been much more organized than the `.zip` file that was turned in
 
2
You now work with two repositories that serve different purposes:
 • class_repo- cloned from the instructor, read-only reference
 • my_repo- your own work, pushed to GitHub
-  Explain why it’s important to keep these separate. What would happen if you tried to put
 everything in one repository?
	- `class_repo` is a read only reference and by combining in any fashion to `my_repo` would most likely create complications with updating `my_repo` with any new files or edits.
- Think about your future coursework or projects. Describe how you might organize multiple
 repositories. For example, how would you handle a group project versus individual assign
ments versus reference materials?
	- For group projects creating a public repository would be very beneficial for other members to be able to access group files and edit, while having a private repository to maintain the work you do consistently would be good practice.

3
- Compare these two commit messages:
 • “update”
 • “Add hw3a solution documenting Git workflow and repository structure”
 Which is more useful? Why? When might you need to find this commit again in the future?
	- The second message is much more useful as it provides essential details to the work that was done. This way anyone reading your work would be able to understand what specific actions were performed without having to run the command themself.
- Imagine you’re working on a data analysis project over several weeks. Describe how you would
 decide when to make a commit. What makes a good “unit of work” for a single commit?
	- Any time there is a significant update to the project you would need to commit. 

