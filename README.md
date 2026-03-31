# Practicing

To add a file inside of the folder using git bash
touch README.md

and to add a content inside of the file using git bash
echo "# comments" > README.md

> " > Overwrites the file content"

> " > >Appends to the existing content"

You can use the cat command to view the contents of the file directly in Git Bash:
cat README.md

Other useful commands to view file contents:
cat README.md - Displays the full content of the file
head README.mdShows - only the first 10 lines
tail README.mdShows - only the last 10 lines
less README.mdOpens - the file in a scrollable view (press q to exit)

** git status ** shows you the current state of your project — what branch you're on, which files are new (untracked), modified, or staged and ready to commit.

instead of:
git add .
git commit -m "comment"

we can short cut using
git commit -a -m "comment"

Question and answers:

> Which Git command skips the staging area when adding a change from our working directory?
>
> > " git commit -a -m "your-commit-message" "

> Which Git command moves changes from committed to the staging area?
>
> > git reset --soft

> Which Git commands create a new branch and checks out to it at the same time?
>
> > git checkout -b new_branch_name

> What are the three stages of a file?
>
> > Committed, modified, staged

> Which Git command initializes a new Git repository in your terminal or command?
>
> > git init

> Which command prompt command returns your current folder path location?
>
> > pwd

> Which Git reset command moves changes from committed to the working directory?
>
> > git reset --mixed

> Which statement is true regarding branches?
>
> > A branch is a pointer to a specific commit in your project.

> Which Git reset command moves changes from committed to the trash?
>
> > git reset --hard

> Which Git command sends your local project to the remote origin?
>
> > git push
