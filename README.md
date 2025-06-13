# Git-And-GitHub-Practice
There, we upload my Git or GitHub journey and the topic that was covered.
Any change in GitHub is a committed change.
Committee means saving the screenshots of my file and storing them in memory.  

          Here, we discuss Git and its commands.
  1 Username Register in our git: <br>
            git config-- global user.name "user name"; <br>
  2 Register the email address that you used on the github. <br>
            git config-- global user.email "example@gmail.com" <br>
  3 Show the Username and userEmail registered successfully/.<br>
          git  config list <br>
  4 Clone: Cloning a repository on our local machine. <br>
          Two things are local(machine or laptop) and remote(That file on Github). <br>
          Clone is used to copy a file from GitHub to the local machine. <br>
     command =>     git clone <-some link of the Project-> <br>
          cd => used to move in a folder or a directory  <br>
  5 ls: It is used to list all files in a specific folder or file. <br>
            ls folder name <br>
    ls -a: Used to show all files also hidden files, in a directory, and if it does not work, then use "ls -Force" <br>
  6 status command: to display the status of the code. <br>
          git status <br>
If we take a change in our file, its status changes and shows it is modified because you don't add or commit. <br>
 We have four statuses in each situation(Exist only one): <br>
           1: Untracked: a new file that git has not yet tracked( when only make a new file but no add or commit). <br>
           2: Modified:  some changes in a file. <br>
           3: unmodified: No change in your file. <br>
           4: Staged: File is ready to be committed. <br>
          look like: <br>
                    change( modified ) or New file( Un tracked ) <br>
                    Add ( staged ) <br>
                    commit( unchanged means all clone is stored ). <br>
  7: add: add new or changed files in your working directory to the Git staging area.
                    git add < -file name- >      
        if we want more then one file then use:
                    git add . (due to this all the files are added in the staging area).
  8: commit: commit the changes to the local repository or it is record of the changes.
        git commit -m "message(meaningful for the changes remembrance)"