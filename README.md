## CLI commands:

##### To delete/undo a SPECIFIC commit history, accidently pushed to remote GitHub repository:
    git reset --hard HEAD~1 
    git push -f <remote> <branch> (ie. git push -f origin main)
    
-   HEAD1 is the ID of the latest top-level commit, you can change it to HEAD~2, HEAD~3, etc depending which commit you want to rollback to
-   this command makes the main/master/header branch rollback to the specific commit (HEAD~1, HEAD~2, etc.), and DELETE all commits UP
-   recommended: test on a sandbox repo, before attempting on production

