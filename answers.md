1. git version 2.17.1
2. user.name=TyLinkous
   user.email=tl987021@ohio.edu
3. The terminal displays a bunch of commands that could help when working with git.
4. The output of the command git status is:
	
	On branch master

	No commits yet

	Untracked files:
  	   (use "git add <file>..." to include in what will be committed)

		README.md
		answers.md

nothing added to commit but untracked files present (use "git add" to track)

5. The output of the git status command after adding the README.md file:
	
	On branch master

	No commits yet

	Changes to be committed:
  	   (use "git rm --cached <file>..." to unstage)

		new file:   README.md

	Untracked files:
  	   (use "git add <file>..." to include in what will be committed)

		answers.md
6. The output of git status after both file are in the staging area:
	
	On branch master

	No commits yet

	Changes to be committed:
  	   (use "git rm --cached <file>..." to unstage)

		new file:   README.md
		new file:   answers.md
7. The output of git status after the git commit command:

	On branch master
	nothing to commit, working tree clean

8. The output of git log:

commit e6c21d2830d60aee707c3bc505eeae1f1bfa49bb (HEAD -> master)
Author: TyLinkous <tl987021@ohio.edu>
Date:   Fri Jan 27 14:23:15 2023 -0500

    Second commit due to missing a step

commit 4d190d935b526a7e29b10718c4c8372262ec1fdc
Author: TyLinkous <tl987021@ohio.edu>
Date:   Fri Jan 27 14:16:53 2023 -0500

    Initial commit

9. The output of git status after git push:

	On branch main
	Your branch is up to date with 'origin/main'.

	nothing to commit, working tree clean

10. No, the changes were not in the local copy.

11. The output of git push:

Authenticated to github.com ([140.82.113.3]:22).
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 403 bytes | 403.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
Transferred: sent 2776, received 2728 bytes, in 0.6 seconds
Bytes per second: sent 4873.0, received 4788.7
To github.com:TyLinkous/git-lab.git
   e6c21d2..d8f11d8  main -> main
tlinkous@odd29:~/git-lab$ git push
Authenticated to github.com ([140.82.114.4]:22).
Transferred: sent 2204, received 2576 bytes, in 0.2 seconds
Bytes per second: sent 11362.5, received 13280.3
To github.com:TyLinkous/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'git@github.com:TyLinkous/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

12. After the git pull command, the changes made in the repository in the git website were present in the local copy. 

13. The output of the ls -a command while in the git-lab-2 file: 
	.  ..  .git  .gitignore  README.md

