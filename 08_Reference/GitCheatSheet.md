Git & Git Bash Commands 
1. Check which branch you’re on git branch

•Shows your current local branch

•* indicates the branch you’re on

Example:
* main
  master
________________________________________
2. Check all branches (local + remote)
git branch -a

• Shows local branches and remote branches

• Remote branches appear as remotes/origin/...
________________________________________
4. Initialize Git (once per local folder)
git init

• Creates a Git repository locally

• You only need this if the folder is new
________________________________________
5. Check status of files
git status

• Shows changes not added yet

• Shows which files are staged / untracked
________________________________________
6. Add files to staging

git add . or for a single file:git add README.md 

• Prepares files for commit

• = all files in folder
________________________________________
7.Commit changes
git commit -m "Your message"

• Saves changes to your local Git history

•Always write clear messages (e.g., “Added test scenarios”)
________________________________________
8.Push to GitHub (remote)
git push -u origin main

• Sends local changes to GitHub

• -u sets upstream branch (first time only)
________________________________________
9.Pull from GitHub

git pull origin main

• Updates your local branch with changes from GitHub
________________________________________
10. Switch / create branch
git checkout branch-name

• Switch to another branch:git checkout -b branch-name origin/branch-name

• Create a local branch tracking a remote branch
________________________________________
11. Delete branches
• Delete local branch:git branch -d branch-name

• Force delete if necessary:git branch -D branch-name

• Delete remote branch:git push origin --delete branch-name

• Or delete via GitHub website (🗑️ icon)
________________________________________
12. Clean stale remote branches

git fetch --prune :Removes deleted remote branches from your local view
________________________________________

13. Check branches

git branch          # shows local branches 

git branch -a       # shows local + remote branches

git status          # shows file changes / staged / untracked
________________________________________
14. Initialize & Connect Repo
git init                           # initialize Git locally

git remote add origin <URL>        # connect to GitHub repo

git remote -v                      # verify GitHub connection
________________________________________
15. Add & Commit Changes
git add .                           # stage all changes

git add <filename>                  # stage specific file

git commit -m "Your message here"   # commit changes locally
________________________________________
Tip: Use clear commit messages:

"Added Test Scenarios for login feature"
________________________________________
16. Push & Pull

git push -u origin main             # push local changes to GitHub

git pull origin main                # update local branch from GitHub
________________________________________
17. Switch / Create Branch

git checkout <branch-name>                   # switch branch

git checkout -b <branch-name> origin/<branch-name>  # create local branch tracking remote
________________________________________
18. Delete Branch
git branch -d <branch-name>       # delete local branch (safe)

git branch -D <branch-name>       # force delete local branch

git push origin --delete <branch-name>  # delete remote branch

Tip: Always stay on a branch other than the one you delete!
________________________________________
19.Clean stale remote branches
git fetch --prune

•Removes references to branches deleted from GitHub
________________________________________
20. Recommended Workflow for Manual Testing Projects

1.	Edit / add files (Test Plan, Test Cases, Bug Reports)

2.	Check status: git status

3.	Stage changes: git add .

4.	Commit: git commit -m "Added test cases"
________________________________________
18.Push to GitHub: git push
________________________________________
19. Quick Checks

git remote -v         # confirm connection to GitHub

git branch            # check current branch

git branch -a         # check all branches

git log --oneline     # see commit history
________________________________________
