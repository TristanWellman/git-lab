# 1.)

Projects/cs2400/git-lab
❯ git --version
git version 2.39.3 (Apple Git-146)

# 2.)

Projects/cs2400/git-lab
❯ git config --global user.name "TristanWellman"

Projects/cs2400/git-lab
❯ git config --global user.email "wellmanboy06@gmail.com
∙

Projects/cs2400/git-lab
❯ git config --global user.email "wellmanboy06@gmail.com"

Projects/cs2400/git-lab
❯ git config --list
credential.helper=osxkeychain
init.defaultbranch=main
user.name=TristanWellman
user.email=wellmanboy06@gmail.com

# 3.)

Running '''git add --help'''

GIT-ADD(1)                                                 Git Manual                                                GIT-ADD(1)

NAME
       git-add - Add file contents to the index

# 4.)

git-lab on  main [!?]
❯ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
    README.md
	answers.md

no changes added to commit (use "git add" and/or "git commit -a")

# 5.)

git-lab on  main [!?]
❯ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	amnswers.md

no changes added to commit (use "git add" and/or "git commit -a")


# 6.)

On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
    new file:   README.md
	new file:   answers.md

# 7.)

git-lab on  main
❯ git status
On branch main
nothing to commit, working tree clean

# 8.)

git-lab on  main [✘!+] took 1m4s
❯ git log
commit 97301514ed289d476d83d12f8fa050180bdee4b7 (HEAD -> main)
Author: TristanWellman <wellmanboy06@gmail.com>
Date:   Thu Sep 5 16:03:44 2024 -0400

    Initial commit




