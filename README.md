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
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git switch ft/team-page
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

Otherwise, please use 'git cherry-pick --skip'
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
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git branch ft/faq-page
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
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout ft/team-page
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
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git branch ft/home-page-redesign
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git checkout main
Switched to branch 'main'
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git add team.html
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
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git rebase main
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
 
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git  commit -m "home page"
[ft/home-page-redesign feab4cd] home page
 1 file changed, 11 insertions(+)
 create mode 100644 home.html
PS C:\Users\tech heaven\OneDrive\Desktop\git exrcise> git push origin ft/home-page-redesign
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
