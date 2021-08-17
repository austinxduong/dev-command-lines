## CLI commands:

##### To delete/undo a SPECIFIC commit history, accidently pushed to remote GitHub repository:
    git reset --hard HEAD~1 (ie. HEAD~1 is the ID of the latest top-level commit)
    git push -f <remote> <branch> (ie. git push -f origin main)

