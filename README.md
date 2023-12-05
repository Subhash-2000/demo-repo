#Demo

Hi welcome to github man. It's greate to start with.

#Subheader

Till now we learnt git such has:
1. git clone git_hub_https_link
2. git cd demo-repo(name of the project in github)
3. la (ls -la which is a shortcut key in linux to list all the files in this directory even hidden files as well)
4. next we opened a README.md file in vscode and did some modification.
5. To save this latest update/modification/changes in git that  we made in README.md file before that we did git status.
   git status command shows me all the files that updated or created or deleted but it haven't been saved in a commit yet.
Note: git add . (Which will add all the modified and untracked files that are in that folder). 
      There is also the command to add the each individual file/folder to git track.
6. Making modified file/folder or created file/folder to git track (By using git add. [or] git add index.html), So it get inside the tracking state of git.
Note: To take the files or folder from git tracking we make use of git restore --staged <file>....".
7. Next we want to do commit with messeage (what and why behind the commit you are doing) that the changes that we made. 
Note: command to commit -> [git commit -m "Added index.html(This is title of the message) -m ""(Message for discription box)]
