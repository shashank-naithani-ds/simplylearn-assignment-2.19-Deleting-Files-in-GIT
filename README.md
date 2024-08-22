# 2.19 Assignment 02 Deleting Files in GIT

<br>
<strong>Problem</strong>
Add two files a.txt and b.txt into a repository. Stage and commit these files. Now delete a.txt from the
Working directory and the staged area, whereas delete b.txt from the staged area but retain in the working directory.
<br><br>
<strong>Solution</strong>
<br><br>
Step: 1 Create file a.txt and b.txt<br>
Step: 2 stage file with $ git add . and commit with $ git commit -m "Initial Upload"<br>
Step: 3 Now Delete a.txt from working and stagging area. $ git rm a.txt<br>
Step: 4 Now Delete b.txt from stagging area only. $ git rm --cached b.txt<br>
Step: 5 check status $ git status will show you untracked files b.txt in the terminal and Denoted with U in the VSCODE file sidebar.<br>
Step: 6 Check history $ git log --online<br>
