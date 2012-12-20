ShadowsandLight.Dec
===================

Newletter
$ mkdir ~/shadowsandlight
# Creates a directory for your project called "Shadows & Light" in your user directory


cd ~/Shadows & Light
# Changes the current working directory to your newly created directory


git init
# Sets up the necessary Git files

# Initialized empty Git repository in /Users/you//Shadows & Light/.git/

touch README
# Creates a file called "README" in your Shadows & Light directory
$ git add README
# Stages your README file, adding it to the list of files to be committed


git commit -m 'first commit'
# Commits your files, adding the message "first commit"
$ git remote add origin https://github.com/shadowsandlight.me/ShadowsandLight.git
# Creates a remote named "origin" pointing at your GitHub repo


git push origin master
# Sends your commits in the "master" branch to GitHub
