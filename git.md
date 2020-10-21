# To setup git

## Git config

One of the first commands we use is config. This command is used to establish user configurations.
We can establish an email or a username that gives us access to a version history

For example, to set up an email:

`git config --global user.email jcabrerap@cifpfbmoll.eu`

To set a user:

`git config --global user.name “[firstname lastname]”`

## git init

To create a new repository we use the command:

`git init`

# to stage & snapshot

## git clone

if we have the repository on a remote server we use the following command:

`git clone [URL]`

## git add

We use this command to add the file is the state it is in for the next commit

`git add exemple.txt`

## git commit

We use this command to make a commit, emphasizing that this will not affect the remote server.

We use -m to add a message to the commit

`git commit -m "add content to de file"`

## git status

If we use this command we have changes to add, it shows us these changes.

`git status`

## git push

With this command we send the changes to the main branch of the remote repository.

`git push`

## git diff

We use this command to see the conflicts

`git diff --base file.txt`

## git reset

To return a file to the working directory we use:

`git reset [file]`

# Branch and merge

## git branch

This command is used to list, create or delete branches

To list the brands we use:

`git branch`

To create a new branch (in the commit we are in) we use:

`git branch [branch name]`

To change the branch we use:

`git checkout`

## git merge

To merge a branch with another active branch we use:

`git merge [branch-name]`

## git log

To merge a branch with another active branch we use:

`git log`


# Inspect and compare

To compare the commits that are in one branch but not in another we use:

`git log branch1..branch2`

To see the commits that changed the file (even if they changed their name) we use:

`git log --follow [file]`

To see the differences between two branches we use:

`git diff branch1...branch2`

To view information about a git object:

`git show`
