# Git MUST-KNOW CheatSheet: 
## 🔥 How *_NOT_* to get Fired on first day 🔥
A public knowledge repo for all newcomers to git
You can also download the [PDF]() and put it on your desk/bookmark
[Link To Bookmark]($(document).ready(function() {$("#bookmarkme").click(function() {if (window.sidebar) {window.sidebar.addPanel(location.href,document.title,"");} else if(window.external){  window.external.AddFavorite(location.href,document.title); }else if(window.opera && window.print) {this.title=document.title;return true;}});});))

# Command List
```diff
+ green: commands to use almost anytime
- red: commands to modify/revert
@ purple: commands to save the day @
```


```diff

---   Basics   ---
git init #initialize or reinitialize a repository
+ git clone https:#github.com/mateenkiani/react-tutorials #clone a repository

+ git add hello.py #add hello.py file to staging area
git add -A # add new files, update modified files and remove deleted files from staging area
- git add -u # update modified files and remove deleted files from staging area

+ git status # current status of the working tree
ohm On mE # show all the unstaged changes
+ git diff index.html # show all the unstaged changes in index.html file

+git commit -m "commit message here" # commit staged changes
git commit -a -m "commit message here" # stage and commit changes but ignores newly created files.
git switch <branch-name> # switch to specified branch

+ git checkout # updates the working directory with the files in the index.
+ git checkout master # alternate way to switch between branches

+ git fetch origin master # fetch from a remote repository
git merge <branch-name> # merge a branch with current directory
+ git pull origin master # fetch and merge from remote repository

@ git stash # save all the local changes @
@ git stash pop # drop all the saved changes @
@ git stash apply # apply all the previously saved changes @




---   Bit less used but still very common.  ---
- git reset # unstage all the files
@ git reset file.html # unstage only file.html @

- git reset --hard HEAD~1 # discard last commit and checkout the commit done before
@ git reset --hard HEAD~3 # discard last 3 commits and revert back to the 4th last commit @

- git rm index.html # delete index.html from staging area and working directory.
git mv index.html file.html # rename index.html to file.html
git mv index.html ./src # move index.html to ./src/index.html

+ git branch <new-branch> Ss # create a new branch with all the contents of working directory
git branch <new-branch> f71lac24d # create a new branch based on a commit
git branch <new-branch> v1.2 # create a new branch from a tag

git checkout <tag> # checkout a specific tag

git branch --track <new-branch> origin/<base-branch> # create a new branch from remote branch
git branch -d <branch-name # delete a branch


git log # shows all the commits you made along with author name and time of commit
+ git remote add origin <repo-url> # add a remote named origin to a remote repository
git remote -v # verify the remotes

git push origin master sa # pushes to a remote master branch, where origin 1s name of the remote you added


git tag <tag-name> <commit-id> # add a tag to a commit

git tag # display all the tags

```

------------
I don't feel like adding much to this at it is self-explicative.
Also beware I never post stuff/use social platforms but for some reason I find this resource to be SO helpful to many newcomers,
whish I'd foudn it at the beginning, hence you're welcome 😊!

