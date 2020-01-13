$git config --global user.name "yunkaibai"//config a global name
$git config --global user.email "812150869@qq.com"//config a global email

$git add readme.txt//add a file to directory
$git commit -m "add a readme file"//commit a change with a note

$git status//check the status of directory

$git diff readme.txt//print the change of readme.txt with linux style

$git log //print the history of change by time
$git reset --hard 9adc//back or forward to the version of directory
$git reflog //print the command history

$git checkout -- readme.txt//undo the change in working and doesn't add to stage
$git reset HEAD readme.txt//undo the file in stage to working directory then use the 'checkout' command to undo the change in working 

$git rm //delete file from repository 

$git remote add origin git@server-name:path/repo-name.git //relate to a remote repository
$git push -u origin master //push all file in master brunch at the first time
$git push origin master //push new change to remote repository

from slave

$git branch //print all branchs
$git branch <name>//create a branch
$git checkout <name> or git switch <name> //swich to other branch
$git checkout -b <name> or git switch -c <name> //create and switch to a branch
$git merge <name> //merge a branch to the branch using now
$git branch -d <name> //delete a branch 