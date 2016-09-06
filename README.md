Go deeper with branching: https://git-scm.com/book/en/v1/Git-Branching-Basic-Branching-and-Merging

To commit you first need to have a git repository.
You can create a brand new one with git init "repository_name" or you can clone an existing one from a URL with git clone "origin_URL" "repository_name".

Then you can modify the repository files or create new ones just like you would in any other folder. Once you're done you need to add the modifications with git add "Files that were modified/created".
You can check what was or wasn't added to the git anytime with the command git status. To remove a file from the git use git reset "file_name" (will keep the file in your folder) or git rm "file_name" (will also remove the file from your computer).
Once everything was correctly added to the git version you can save that version with git commit (or git commit -m "version_name").
