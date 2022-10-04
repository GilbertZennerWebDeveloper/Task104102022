#create an initial commit

only one person is doing this

Create a file in your folder (readme.md)
git add .
git commit -m "initial commit"
git push (password problem: open git bash as admin and paste:git config --system --unset credential.helper)

Task:
-each coworker in the group creates a branch. Use a name like feature/name-of-the-feature. Pretend you are working on a specific task

-modify some files
-do a git add (track/stage) and create a commit
-push your branch
-other coworkers should see them (after a git fetch or after gitkraken refreses the view)

#merge

-merge your branch locally on master
-push master new version
-other coworker pulls the new master
-other coworker pulls their branches one by one in their local master and push master new version


#pull request

-each dev creates a local branch
-add some commits (work on something)
-each push the feature branch
-each dev opens a pull request (PR)
-request a review from your coworker
-the other one approves or ask for modification
-merge on github
-pull the new master locally
-remov the merged feature branch (both local and remote)