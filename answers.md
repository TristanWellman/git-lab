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


# 9.)

git-lab on  main took 11s
❯ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

# 10.)

Nothing was in README because it's not synced.

# 11.)

git-lab on  main [!] took 31s
❯ git push -u origin main
To https://github.com/TristanWellman/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/TristanWellman/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

# 12.)

git-lab on  main [!] took 14s
❯ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 960 bytes | 240.00 KiB/s, done.
From https://github.com/TristanWellman/git-lab
   7b52025..9332b90  main       -> origin/main
Updating 7b52025..9332b90
Fast-forward
 README.md | 1 +
 1 file changed, 1 insertion(+)

 # 13.)

git-lab-2 on  main
❯ ls -a
.		..		.git		.gitignore	README.md
