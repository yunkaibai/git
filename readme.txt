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