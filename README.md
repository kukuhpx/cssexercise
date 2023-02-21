Repository latihan CSS dan pengembangan UI/UX web, selain itu terdapat Dev Notes di sini.

GIT COMMAND
Checking GIT Version:
> git -v
Creating a New GIT Repo:
> git init
Checking Staging Files:
> git status
Adding Files to Staging Environment:
> git add [file name].[file format]
> git add --all
> git add -A
> git add *
> git add .
Commiting All Staged Files:
> git commit -m ["your message"]
> git commit -am ["your message"]
Checking Braanch You Owned:	
> git branch
Creating a New Repo Branch:
> git branch -M [new branch name]	
> git branch [branch name]
Switching Repo Branch:
> git checkout [your branch name]
Changing Repo Branch's Name:
> git branch -m [new branch's name]
Deleting Repo Branch's Name:
> git branch -d [branch's name]
Deleting a Folder:
> git rm -r [folder's name]

GITHUB COMMAND
Changing Remote URL:
1. > git remote set-url origin [new remote url].
2. > git fetch origin master.
3. > git pull origin master.
4. > git push origin master.

Checking The Remote You Owned:
> git remote -v
Creating a GitHub Remote:
> git remote add [remote name] [remote url]
Changing a Remote Name:
> git remote rename [old remote name] [new remote name]
Deleting a Remote:
> git remote remove [remote name]
Showing Remote Information:
> git remote show [remote name]
Changing Remote URL:
> git remote set-url [remote name] [remote url]
Uploading Your Repository to GitHub:
> git push [remote name] [branch name]
Forcing Upload Your Repository to GitHub:
> git push -f [remote name] [branch name]
Downloading Your Commit without Merge Your Local Branch:
> git pull [remote name] [branch name]
Downloading Your Commit with Merge Your Local Branch:
> git fetch [remote name] [branch name]
Downloading Your Repository in GitHub:
> git clone [your git url in github]

DEV NOTES
Beberapa pasangan property:
1. (Sibling) float >< (Sibling) clear.
2. position(relative, absolute dan fixed) >< top/right/botto/left.
3. (Parent) display: table >< (Child) display: table-cell.
4. display: flex >< justify-content/align-item/align-content.
Daftar inline HTML elemen:
1. <a></a>
2. <b></b>
3. <button></button>
4. <i></i>
5. <img>
6. <input>
7. <strong></strong>
Daftar block HTML elemen:
1. <div></div>
2. <form></form>
3. <h1></h1> - <h6></h6>
4. <p></p>