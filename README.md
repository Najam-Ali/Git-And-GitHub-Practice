# Git-And-GitHub-Practice
There, we upload my Git or GitHub journey and the topic that was covered.
Any change in GitHub is a committed change.
Committee means saving the screenshots of my file and storing them in memory.  

          Here, we discuss Git and its commands.
  1 Username Register in our git:
            git config-- global user.name "user name";
  2 Register the email address that you used on the github.
            git config-- global user.email "example@gmail.com"
  3 Show the Username and userEmail registered successfully/.
          git  config list
  4 Clone: Cloning a repository on our local machine.
          There are two things that are local(machine or laptop) and remote(That file on Github).
          Clone is used to copy a file from GitHub to the local machine.
     command =>     git clone <-some link of the Project->
          cd => used to move in a folder or a directory 
  5 ls: It is used to list all files in a specific folder or file.
            ls folder name
    ls -a: Used to show all files also hidden files, in a directory, and if it does not work, then use "ls -Force"
  6 status command: to display the status of the code.
          git status
If we take a change in our file, its status changes and shows it is modified because you don't add or commit.
 We have four statuses in each situation(Exist only one):
           1: Untracked: a new file that git has not yet tracked( when only make a new file but no add or commit).
           2: Modified:  some changes in a file.
           3: unmodified: No change in your file.
           4: Staged: File is ready to be committed. 
          look like:
                    change( modified ) or New file( Un tracked )
                    Add ( staged )
                    commit( unchanged means all clone is stored ).
  7: add: add new or changed files in your working directory to the Git staging area.
          









