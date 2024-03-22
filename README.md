Step 1. Create new repo 
    `git init -b main ./new-project`
    `cd ./new-project`
    
Step 2. Create README.md file 
    `touch README.md`

Step 3. Commit it 
    `git add README.md`
    `git commit -m "init"`

Step 4. Create new branch "development" 
    `git checkout -b development`

Step 5. Make some changes 

Step 6. Commit it 
    `git add README.md`
    `git commit -m "New branch"`

Step 7. Merge development and main 
    `git merge main`

Step 8. Merge main and development commits 
   `git merge development`

Step 9. Push it to public repo 
    `git push origin main`