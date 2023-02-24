The repository for CSS exercise, there is a DEV NOTES to note all important things here.
The repo was also included the GIT COMMAND and GITHUB COMMAND for additional purpose.

GIT COMMAND
1. Checking GIT Version:
    > git -v
2. Creating a New GIT Repo:
    > git init
3. Checking Staging Files:
    > git status
4. Adding Files to Staging Environment:
    > git add [file's name].[file format]
    > git add --all
    > git add -A
    > git add *
    > git add .
5. Commiting All Staged Files:
    > git commit -m ["your message"]
    > git commit -am ["your message"]
6. Checking Braanch You Owned:	
    > git branch
7. Creating a New Repo Branch:
    > git branch -M [new branch's name]	
    > git branch [branch name]
8. Switching Repo Branch:
    > git checkout [your branch's name]
9. Changing Repo Branch's Name:
    > git branch -m [new branch's name]
10. Deleting Repo Branch's Name:
    > git branch -d [branch's name]
11. Deleting a Folder:
    > git rm -r [folder's name]
12. Checking The Remote You Owned:
    > git remote -v
13. Creating a GitHub Remote:
    > git remote add [remote's name] [remote url]
14. Changing a Remote Name:
    > git remote rename [old remote's name] [new remote name]
15. Deleting a Remote:
    > git remote remove [remote's name]
16. Showing Remote Information:
    > git remote show [remote's name]
17. Changing Remote URL:
    > git remote set-url [remote's name] [remote url]
18. Uploading Your Repository to GitHub:
    > git push [remote's name] [branch's name]
19. Forcing Upload Your Repository to GitHub:
    > git push -f [remote's name] [branch's name]
20. Downloading Your Commit without Merge Your Local Branch:
    > git pull [remote's name] [branch's name]
21. Downloading Your Commit with Merge Your Local Branch:
    > git fetch [remote's name] [branch's name]
22. Downloading Your Repository in GitHub:
    > git clone [your git url in github]

GITHUB COMMAND
1. > git remote set-url [remote's name] [new remote's url].
2. > git fetch [remote's name] [branch's name].
3. > git pull [remote's name] [branch's name].
4. > git push [remote's name] [branch's name].git

DEV NOTES
Couple CSS's Property:
1. (sibling) {float: left/right} & (sibling) {clear: left/right/both}.
2. (self) {position: relative/absolute/fixed} & (self) {top/right/botto/left}.
3. (parent) {display: table} & (child) {display: table-cell}.
4. (self) {display: flex} & (self) {justify-content/align-item/align-content}.
5. (img) {max-width/max-height} (img) {overflow: hidden/scroll/auto}.
Inline HTML's Element List:
1. <a></a>
2. <b></b>
3. <button></button>
4. <i></i>
5. <img>
6. <input>
7. <strong></strong>
Block HTML's Element List:
1. <div></div>
2. <form></form>
3. <h1></h1> - <h6></h6>
4. <p></p>