## CLI commands:

##### To delete/undo a SPECIFIC commit history, accidently pushed to remote GitHub repository:
    git reset --hard HEAD~1 
    git push -f <remote> <branch> (ie. git push -f origin main)
    
-   HEAD1 jumps 1 previous commit ID. You can change it to HEAD2, HEAD3, etc depending which commit you want to rollback to
-   this command makes the main/master/head branch rollback to the specific commit (HEAD1, HEAD2, etc.), and DELETES all commits UP. No history or trace of this action will appear on the GitHub remote repository. All commits below remain in tact. This is good if you accidently push a commit you did not intend.
-   recommended: test on a sandbox repo, before attempting on production

