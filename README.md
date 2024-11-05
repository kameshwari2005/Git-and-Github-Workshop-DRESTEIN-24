# Git-and-Github-Workshop-DRESTEIN-24
NAME: KAMESHWARI M
REGISTER NUMBER :  212222060110
DEPARTMENT :  ECE
YEAR :  3
### Git and GitHub Workshop Assignment
Complete the following tasks to practice core Git commands. Answer each question and perform the associated Git operations. 
# 1. Setup and Initialize: 
- What command do you use to create a new directory named git-workshop and 
navigate into it? <br>
Answer :     mkdir git-workshop <br>
             cd git-workshop <br>
# 2. Initialize a Git Repository: 
- What command initializes a Git repository in your directory?  <br>
Answer: git init
# 3.Create and Modify Files: 
- How do you create a new file named hello.txt and add the content 'Hello, GitWorkshop!' to it using a single command?  <br>
Answer : echo "Hello, Git Workshop!" > hello.txt
# 4. Check the Status of Your Repository: 
- What command displays the status of your repository? <br> 
Answer:  git status
# 5.  Stage and Commit Changes: 
- What command stages the file hello.txt?  <br>
Answer: git add hello.txt
- What command commits the staged file with the message 'Add hello.txt with 
welcome message'? <br> 
Answer: git commit -m "Add hello.txt with welcome message"
# 6. Branching: 
- What command creates a new branch named update-content? <br> 
Answer: git branch update-content
- How do you switch to the update-content branch? <br>
Answer: git checkout update-content 
# 7. Make Changes on the Branch:
- What command would you use to append the text 'This is a simple Git assignment.' to 
hello.txt?  <br>
Answer: echo "This is a simple Git assignment." >> hello.txt  <br>
- What command stages and commits the changes with the message 'Update hello.txt 
with additional message'?  <br>
answer:  git add hello.txt  <br>
         git commit -m "Update hello.txt with additional message"
# 8. Merge Changes: 
- What command switches you back to the main branch?  <br>
Answer: git checkout main
- How do you merge the update-content branch into main? <br>
Answer: git merge update-content 
# 9.  View Commit History: 
- What command shows the commit history? <br>
Answer : git log
# 10. Undo and Reset (Practice Safely): 
- If you make a change to hello.txt that you want to revert before committing, what 
command would you use?  <br>
Answer : git restore hello.txt <br>
- How can you reset your branch to a previous commit (optional, for advanced 
practice)?  <br>
Answer : git reset --hard <commit-hash>
# 11. Push to a Remote Repository (Optional): 
- What command adds a remote repository named origin? <br> 
Answer: git remote add origin <repository-url>
- What command pushes your local main branch to the remote repository? <br>
Answer :  git push origin main
