Set up new Git repository and create development branch for 'new-project'

Steps:
1. Open Terminal
2. Create new catalogue named "new-project" using command 'mkdir -p /Users/nickpimankov/Desktop/new-project'
3. Go to newly created catalogue using command 'cd /Users/nickpimankov/Desktop/new-project'
4. Initialize new Git rep in the catalogue using command 'git init'
5. Create a new file named "README.md" using command 'touch README.md'
6. Open the file using command 'nano README.md', enter required text and save the changes (Control+X -> Y -> Enter)
7. Prepare the file for commit using command 'git add README.md'
8. Commit the file into repo with commit message "init" using command 'git commit -m "init"'
9. Create new branch named "development" and go there using command 'git checkout -b development'
10. Add step-by-step instructions to README.md and prepare for commit using command 'git add README.md'
11. Commit the changes in "development" branch with the message using command 'git commit -m "Add rep setup and branch creation instructions"'
12. Merge changes in "development" branch into "main" using commands 'git checkout main' and 'git merge development'
13. Check the status using command 'git status'
14. Commit the changes using command 'git commit -m "Final"'

