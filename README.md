1. **Create a new directory for your project**
  - Open your terminal or command prompt
  - Navigate to the desired location
  - Run the command: `mkdir new-project`

2. **Navigate into the new directory**
  - Run the command: `cd new-project`

3. **Initialize a new Git repository**
  - Run the command: `git init`

4. **Add remote repository**
  - Run the commad: `git remote add origin <URL of remote repositroy>`

5. **Create and switch to a new branch named "development"**
  - Run the command: `git switch -c  development`

6. **Stage and commit the changes in the "development" branch**
  - Run the command: `git add <Changed object>`
  - Run the command: `git commit -m "Description of commit"`

7. **Switch back to the "main" branch**
   - Run the command: `git switch main`

8. **Merge the changes from the "development" branch into the "main" branch**
   - Run the command: `git merge development`

9. **Check the status of the repository**
   - Run the command: `git status`

10. **Push the changes to your remote GitHub repository**
   - Run the command: `git push origin main`
