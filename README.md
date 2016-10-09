### gitInit for my own workspace

first git setup from Udacity - How to Use Git and GitHub (lesson 1 - 29/33)

git config --global user.name "Francesco Marangione"
git config --global user.email mft@mftnet.com
git config --global core.editor subl
git config --global color.diff auto

alias subl="/Applications/Sublime\ Text\ 2.app/Contents/SharedSupport/bin/subl"

https://git-scm.com/book/it/v2/Customizing-Git-Git-Configuration

### init project

git init
vi .git/info/exclude 
git add .
git commit -m 'FILENAME, changelog'

### push project to gitHub

git remote add origin https://github.com/mft3000/xxxxxxxx.git
git remote -v
git push -u origin master
