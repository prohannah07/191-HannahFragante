Answer to questions

1)Use git status to see which branch you are on.
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git status

2) What does git log look like?
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git log
fatal: your current branch 'master' does not have any commits yet

3)Create a file
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ touch README.md

4) What does the output from git status look like now?
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
    README.md

nothing added to commit but untracked files present (use "git add" to track)

5) add the file to the staging area
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git add .

6) How does git status look now?
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
    new file:   README.md

7) commit the file to the repository
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git commit -m 'added README'

8) How does git status look now?
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git status
On branch master
nothing to commit, working tree clean

9) Change the content of the file you created earlier
Im changing the content now

10) What does git status look like now?
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
    modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

11) add the file change
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git add .

12) What does git status look like now?
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
    modified:   README.md


13) Change the file again
CHANGING THE FILE AGAIN

14) Make a commit
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git commit -m 'changed README'

15) What does the status look like now? The log?
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git status
On branch master
nothing to commit, working tree clean

Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git log
commit b849bccf966f5f82bacffe092c9eee93e171a0a9 (HEAD -> master)
Author: Hannah Fragante <hfragant@uci.edu>
Date:   Fri Jan 24 03:28:10 2020 -0800

    changed README again

commit 058bfc370a6742ae8e9d28bad1c1a9ead9275515
Author: Hannah Fragante <hfragant@uci.edu>
Date:   Fri Jan 24 03:27:09 2020 -0800

    changed README

commit 8d4b2c7ac8048c03e88958e88cd9e80cb6c7e614
Author: Hannah Fragante <hfragant@uci.edu>
Date:   Fri Jan 24 03:24:33 2020 -0800

    added README

16) Commit the newest change
Hannahs-MacBook-Pro-2:exercise hannah07fragante$ git commit -m 'final changes to README'
[master bbd9514] final changes to README
 1 file changed, 26 insertions(+)

