## GitHub CLI Commands:

##### To delete/undo a SPECIFIC commit history, accidently pushed to remote GitHub repository:
    git reset --hard HEAD~1 
    git push -f <remote> <branch> (ie. git push -f origin main)
    
-   `HEAD~1` jumps 1 previous commit ID. 
-   You can change it to `HEAD~2`, `HEAD~3`, etc., depending which commit you want to rollback to.
-   This command makes the main/master/head branch rollback to the specific commit (`HEAD~1`, `HEAD~2`, etc.), and DELETES all commits UP. All commits below remain in tact. No history or trace of this action will appear on the GitHub remote repository (list of commit history). This is good if you accidently push a commit you did not intend.
-   Recommended: test on a sandbox repo, before attempting on production

## CLI Commands (General):

##### To Delete a directory(folder), and all files/contents inside:
    rm -rf <directory name>
-   Deletes directory (folder), and any files inside.

