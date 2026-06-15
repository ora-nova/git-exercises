bundle 3 exercise1
`````
PS C:\Users\tech heaven\OneDrive\Desktop> cd "git exrcise"
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git branch main
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout ft/team-page
Already on 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout main
Switched to branch 'main'
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git branch ft/contact-page
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git switch ft/team-page // question 1
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git log
commit 0353690c5f83efe6fb955a74802f37a870ef83cc (HEAD -> ft/team-page, origin/ft/team-page, main, ft/contact-page)
Author: ora-nova <shyakauwaseoranova@gmail.com>
Date:   Wed Jun 10 14:23:31 2026 +0200

    update

commit 86beafbc5627f5604ae2823b1012c8f173073301
Author: ora-nova <shyakauwaseoranova@gmail.com>
Date:   Wed Jun 10 13:47:21 2026 +0200

    team page
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git log --oneline -1
0353690 (HEAD -> ft/team-page, origin/ft/team-page, main, ft/contact-page) update
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout ft/contact-page
Switched to branch 'ft/contact-page'
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git log --oneline ft/team-page -1
0353690 (HEAD -> ft/contact-page, origin/ft/team-page, main, ft/team-page) update
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git cherry-pick 0353690
On branch ft/contact-page
You are currently cherry-picking commit 0353690.
  (all conflicts fixed: run "git cherry-pick --continue")
  (use "git cherry-pick --skip" to skip this patch)
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)

nothing to commit, working tree clean
The previous cherry-pick is now empty, possibly due to conflict resolution.
If you wish to commit it anyway, use:

    git commit --allow-empty

Otherwise, please use 'git cherry-pick --skip' // question 6
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout ft/conatct-page
error: pathspec 'ft/conatct-page' did not match any file(s) known to git
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout ft/contact-page
Already on 'ft/contact-page'
warning: cancelling a cherry picking in progress
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git add contact.html
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git commit -m "update on contact page"
[ft/contact-page 6702777] update on contact page
 1 file changed, 11 insertions(+)
 create mode 100644 contact.html
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git push origin ft/contact-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 465 bytes | 7.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/ora-nova/git-exercises/pull/new/ft/contact-page
remote: 
To https://github.com/ora-nova/git-exercises
 * [new branch]      ft/contact-page -> ft/contact-page
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git branch ft/faq-page // question 9
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout ft/faq-page
Switched to branch 'ft/faq-page'
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git add faq.html
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git commit -m "the faq page"
[ft/faq-page dae7dd9] the faq page
 1 file changed, 11 insertions(+)
 create mode 100644 faq.html
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git push origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 471 bytes | 67.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/ora-nova/git-exercises/pull/new/ft/faq-page
remote: 
To https://github.com/ora-nova/git-exercises
 * [new branch]      ft/faq-page -> ft/faq-page
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout ft/team-page // question 12
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git revert 0353690 
[ft/team-page e643f1f] Revert "update"
 1 file changed, 1 deletion(-)
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git push origin ft/team-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 7.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
`````
exercise2
`````
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git branch ft/home-page-redesign // question 1
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout main // question2
Switched to branch 'main'
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git add team.html // question 3
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git commit -m "updated team.html"
[main 8e6c048] updated team.html
 1 file changed, 1 insertion(+)
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 313 bytes | 14.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ora-nova/git-exercises
   86beafb..8e6c048  main -> main
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout main
Switched to branch 'main'
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git pull origin main
From https://github.com/ora-nova/git-exercises
 * branch            main       -> FETCH_HEAD
Already up to date.
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git rebase main// question 5
Auto-merging team.html
CONFLICT (content): Merge conflict in team.html
error: could not apply e643f1f... Revert "update"
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
hint: Disable this message with "git config set advice.mergeConflict false"
Could not apply e643f1f... # Revert "update"
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> 
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git add team.html
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git rebase --continue
[detached HEAD 7d9ddf4] Revert "update"
 1 file changed, 3 insertions(+)
Successfully rebased and updated refs/heads/ft/home-page-redesign.
To https://github.com/ora-nova/git-exercises
   0353690..e643f1f  ft/team-page -> ft/team-page
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git add home.html
 
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git  commit -m "home page"// question 6
[ft/home-page-redesign feab4cd] home page
 1 file changed, 11 insertions(+)
 create mode 100644 home.html
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git push origin ft/home-page-redesign // question 7
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 2 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 692 bytes | 115.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/ora-nova/git-exercises/pull/new/ft/home-page-redesign
remote: 
To https://github.com/ora-nova/git-exercises
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
`````
Bundle 4 exercise 1
```````

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/footer) //question 1
$ git add foot.html

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/footer)
$ git commit -m "foot page"
[ft/footer 8b818bc] foot page
 1 file changed, 11 insertions(+)

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/footer)
$ git status
On branch ft/footer
nothing to commit, working tree clean

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/footer)
$  git status
On branch ft/footer
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   foot.html

no changes added to commit (use "git add" and/or "git commit -a")

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/footer)
$ git add --all

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/footer)
$ git commit -m "new changes"
[ft/footer 1b105d0] new changes
 1 file changed, 6 insertions(+)

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/footer)
$ git push
fatal: The current branch ft/footer has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/footer

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/footer)
$ git push --set-upstream origin ft/footer
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 816 bytes | 29.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/ora-nova/git-exercises
   9fcc4e5..1b105d0  ft/footer -> ft/footer
branch 'ft/footer' set up to track 'origin/ft/footer'.

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/footer)
$ git checkout main // question 5
Switched to branch 'main'

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (main)
$ git branch ft/squashing

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (main)
$ git checkout ft/squashing
Switched to branch 'ft/squashing'

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/squashing)
$ git status
On branch ft/squashing
nothing to commit, working tree clean

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/squashing)
$  git merge --squash ft/footer //question 7
Auto-merging foot.html
CONFLICT (add/add): Merge conflict in foot.html
Squash commit -- not updating HEAD
Automatic merge failed; fix conflicts and then commit the result.


tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/squashing)
$ git status
On branch ft/squashing
Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add <file>..." to mark resolution)
        both added:      foot.html

no changes added to commit (use "git add" and/or "git commit -a")

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/squashing)
$ git add foot.html

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/squashing)
$ git commit -m "squash footer into main branch"
[ft/squashing 3aa55ed] squash footer into main branch
 1 file changed, 7 insertions(+), 3 deletions(-)

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/squashing)
$  git status
On branch ft/squashing
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   foot.html

no changes added to commit (use "git add" and/or "git commit -a")

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/squashing)
$ git add foot.html

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/squashing)
$ git commit -m "footer changes squashing"
[ft/squashing 1306d71] footer changes squashing
 1 file changed, 1 insertion(+), 1 deletion(-)

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/squashing)
$ git push
fatal: The current branch ft/squashing has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/squashing

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/squashing)
$  git push --set-upstream origin ft/squashing
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 2 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (12/12), 1.43 KiB | 34.00 KiB/s, done.
Total 12 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), done.
remote: 
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/ora-nova/git-exercises/pull/new/ft/squashing
remote: 
To https://github.com/ora-nova/git-exercises
 * [new branch]      ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'origin/ft/squashing'.
```````
bundle5 exercise2
```````
$ git clone https://github.com/ora-nova/git-cafe-exercise // question 2
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects:   6% remote: Counting objects:  13% remote: Counting objects:  20% remote: Counting objects:  26% remote: Counting objects:  33% remote: Counting objects:  40% remote: Counting objects:  46% remote: Counting objects:  53% remote: Counting objects:  60% remote: Counting objects:  66% remote: Counting objects:  73% remote: Counting objects:  80% remote: Counting objects:  86% remote: Counting objects:  93% remote: Counting objects: 100% remote: Counting objects: 100% (15/15), done.
remote: Compressing objects:   remote: Compressing objects:  1remote: Compressing objects:  2remote: Compressing objects:  3remote: Compressing objects:  4remote: Compressing objects:  5remote: Compressing objects:  6remote: Compressing objects:  7remote: Compressing objects:  8remote: Compressing objects:  9remote: Compressing objects: 10remote: Compressing objects: 100% (11/11), done.
Receiving objects:   9% (10/107Receiving objects:  10% (11/107Receiving objects:  11% (12/107Receiving objects:  12% (13/107Receiving objects:  13% (14/107Receiving objects:  14% (15/107Receiving objects:  15% (17/107Receiving objects:  16% (18/107Receiving objects:  17% (19/107Receiving objects:  18% (20/107Receiving objects:  19% (21/107Receiving objects:  20% (22/107Receiving objects:  21% (23/107Receiving objects:  22% (24/107Receiving objects:  23% (25/107Receiving objects:  24% (26/107Receiving objects:  25% (27/107Receiving objects:  26% (28/107Receiving objects:  27% (29/107Receiving objects:  28% (30/107Receiving objects:  29% (32/107Receiving objects:  30% (33/107Receiving objects:  31% (34/107Receiving objects:  32% (35/107Receiving objects:  32% (35/107Receiving objects:  33% (36/107Receiving objects:  34% (37/107Receiving objects:  35% (38/107Receiving objects:  36% (39/107Receiving objects:  37% (40/107Receiving objects:  38% (41/107Receiving objects:  39% (42/107Receiving objects:  40% (43/107Receiving objects:  41% (44/107Receiving objects:  42% (45/107Receiving objects:  43% (47/107Receiving objects:  44% (48/107Receiving objects:  45% (49/107Receiving objects:  46% (50/107Receiving objects:  47% (51/107Receiving objects:  48% (52/107Receiving objects:  49% (53/107Receiving objects:  50% (54/107Receiving objects:  51% (55/107Receiving objects:  52% (56/107Receiving objects:  53% (57/107Receiving objects:  54% (58/107Receiving objects:  55% (59/107Receiving objects:  56% (60/107Receiving objects:  57% (61/107Receiving objects:  58% (63/107Receiving objects:  59% (64/107Receiving objects:  60% (65/107Receiving objects:  61% (66/107Receiving objects:  62% (67/107Receiving objects:  63% (68/107Receiving objects:  64% (69/107Receiving objects:  65% (70/107Receiving objects:  66% (71/107Receiving objects:  67% (72/107Receiving objects:  68% (73/107Receiving objects:  69% (74/107Receiving objects:  70% (75/107Receiving objects:  71% (76/107Receiving objects:  72% (78/107Receiving objects:  73% (79/107Receiving objects:  74% (80/107Receiving objects:  75% (81/107Receiving objects:  76% (82/107Receiving objects:  77% (83/107Receiving objects:  78% (84/107Receiving objects:  79% (85/107Receiving objects:  80% (86/107Receiving objects:  81% (87/107Receiving objects:  82% (88/107Receiving objects:  83% (89/107Receiving objects:  84% (90/107Receiving objects:  85% (91/107Receiving objects:  86% (93/107Receiving objects:  87% (94/107Receiving objects:  88% (95/107Receiving objects:  89% (96/107Receiving objects:  90% (97/107Receiving objects:  91% (98/107Receiving objects:  92% (99/107Receiving objects:  93% (100/10Receiving objects:  94% (101/10Receiving objects:  95% (102/10Receiving objects:  96% (103/10remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 92 (from 1)
Receiving objects:  97% (104/10Receiving objects:  98% (105/10Receiving objects:  99% (106/10Receiving objects: 100% (107/10Receiving objects: 100% (107/107), 1.95 MiB | 535.00 KiB/s, done.
Resolving deltas: 100% (5/5), done.

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise (ft/squashing)
$ cd git-cafe-exercise

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main) // question 5
$ git add index.html

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main)
$ git commit -m "Change welcome message to restaurant"
[main 0baee6e] Change welcome message to restaurant
 1 file changed, 1 insertion(+), 1 deletion(-)

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 336 bytes | 67.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/ora-nova/git-cafe-exercise
   d1d3f9c..0baee6e  main -> main
``````` 
bundle 6 exercise 1
```````
tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main)
$ git branch ft/menu // question 1

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main)
$ 

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main)
$ touch menu.html

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main)
$ git checkout ft/menu
Switched to branch 'ft/menu'

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (ft/menu)
$ git add menu.html // question 2

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (ft/menu)
$ git commit -m "Add Menu page"
[ft/menu b5e082e] Add Menu page
 1 file changed, 11 insertions(+)
 create mode 100644 menu.html

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (ft/menu)
$ git push origin ft/menu
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 437 bytes | 43.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/menu' on GitHub by visiting:
remote:      https://github.com/ora-nova/git-cafe-exercise/pull/new/ft/menu
remote: 
To https://github.com/ora-nova/git-cafe-exercise
 * [new branch]      ft/menu -> ft/menu
```````
exercise 2
```````
tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (ft/menu)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main)
$ git pull origin main
From https://github.com/ora-nova/git-cafe-exercise
 * branch            main       -> FETCH_HEAD
Already up to date.

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main)
$ git checkout -b bugfix-contact-title // question 1
Switched to a new branch 'bugfix-contact-title'

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (bugfix-contact-title)
$ git add index-4.html // question 2

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (bugfix-contact-title)
$ git commit -m "Fix contact page title"
[bugfix-contact-title d9a0447] Fix contact page title
 1 file changed, 1 insertion(+), 1 deletion(-)

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (bugfix-contact-title)
$ git push origin bugfix-contact-title
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 310 bytes | 51.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'bugfix-contact-title' on GitHub by visiting:
remote:      https://github.com/ora-nova/git-cafe-exercise/pull/new/bugfix-contact-title
remote: 
To https://github.com/ora-nova/git-cafe-exercise
 * [new branch]      bugfix-contact-title -> bugfix-contact-title
```````
exercise 4
``````
tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (bugfix-contact-title)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main)
$ git pull origin main
From https://github.com/ora-nova/git-cafe-exercise
 * branch            main       -> FETCH_HEAD
Already up to date.

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (main)
$ git checkout -b hotfix-contact-phone // question 1
Switched to a new branch 'hotfix-contact-phone'

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (hotfix-contact-phone)
$ git add index-4.html

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (hotfix-contact-phone)
$ git commit -m "Fix contact phone number"
[hotfix-contact-phone 75b9eb8] Fix contact phone number
 1 file changed, 1 insertion(+), 1 deletion(-)

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/OneDrive/Desktop/git exrcise/git-cafe-exercise (hotfix-contact-phone)
$ git push origin hotfix-contact-phone
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 306 bytes | 21.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'hotfix-contact-phone' on GitHub by visiting:
remote:      https://github.com/ora-nova/git-cafe-exercise/pull/new/hotfix-contact-phone
remote: 
To https://github.com/ora-nova/git-cafe-exercise
 * [new branch]      hotfix-contact-phone -> hotfix-contact-phone
``````
