## BUNDLE 2
# EXERCISE 2
```
PS C:\Users\student\Downloads\git_exercise> git status
On branch ft/service-redesign
Your branch is up to date with 'origin/ft/service-redesign'.

nothing to commit, working tree clean
PS C:\Users\student\Downloads\git_exercise> 
 *  History restored 

On branch ft/service-redesign
Your branch is up to date with 'origin/ft/service-redesign'.

  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\student\Downloads\git_exercise> git add --all
PS C:\Users\student\Downloads\git_exercise> git commit -m "added new changes to services html"
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\student\Downloads\git_exercise> git push --set-upstream origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 343 bytes | 171.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/AL2002MI08/Git-exercise.git
   cd6fbae..032dbf7  ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.
PS C:\Users\student\Downloads\git_exercise> git mergetool
error: cannot spawn git-sh-i18n--envsubst: Permission denied

This message is displayed because 'merge.tool' is not configured.
See 'git mergetool --tool-help' or 'git help config' for more details.
'git mergetool' will now attempt to use one of the following tools:
tortoisemerge emerge vimdiff nvimdiff
No files need merging
PS C:\Users\student\Downloads\git_exercise> git checkout main
Switched to branch 'main'
PS C:\Users\student\Downloads\git_exercise> git add --all
PS C:\Users\student\Downloads\git_exercise> git commit -m "added list of instruction to service page"
 1 file changed, 22 insertions(+)
 create mode 100644 services.html
PS C:\Users\student\Downloads\git_exercise> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\student\Downloads\git_exercise> git push --set-upstream origin main
To https://github.com/AL2002MI08/Git-exercise.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/AL2002MI08/Git-exercise.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\student\Downloads\git_exercise> git pull origin main
From https://github.com/AL2002MI08/Git-exercise
 * branch            main       -> FETCH_HEAD
CONFLICT (add/add): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.
PS C:\Users\student\Downloads\git_exercise> git commit -m "resolved conflicts merge"
[main 6e9201c] resolved conflicts merge
PS C:\Users\student\Downloads\git_exercise> git push origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 970 bytes | 323.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/AL2002MI08/Git-exercise.git
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.
PS C:\Users\student\Downloads\git_exercise> git merge main
Auto-merging services.html
CONFLICT (add/add): Merge conflict in services.html
PS C:\Users\student\Downloads\git_exercise> git commit -m "merge"
On branch ft/service-redesign
Your branch is ahead of 'origin/ft/service-redesign' by 10 commits.
  (use "git push" to publish your local commits)

PS C:\Users\student\Downloads\git_exercise>
PS C:\Users\student\Downloads\git_exercise> git commit -m "merge and resolve conflicts"
On branch ft/service-redesign
Your branch is ahead of 'origin/ft/service-redesign' by 10 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\student\Downloads\git_exercise> git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 415 bytes | 207.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/AL2002MI08/Git-exercise.git
   032dbf7..f8cc145  ft/service-redesign -> ft/service-redesign
PS C:\Users\student\Downloads\git_exercise>

```
