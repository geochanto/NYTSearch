1. Pseudo-Coding
2. Create Issues 
3. Assign Issues
4. Move issue from Backlog to In-progress
5. Make sure you are in master branch. Pull from master. Create branch from master. `git checkout -b BRANCH-NAME`
6. Add and Commit changes as you make them. 
7. Test all changes locally. 
8. Switch to master: `git checkout master`
9. Pull from master. `git pull origin master`
10. Switch back to branch you were working on: `git checkout BRANCH-NAME`
11. Merge latest master into current branch: `git merge master`
12. Fix any merge conflicts. 
13. Push branch up to Github: `git push origin BRANCH-NAME`
14. Create a pull request and add person to the pull request. 
15. Once reviewed, have person reviewing merge the pull request and then delete the branch from Github. 
16. Checkout master: `git checkout master`
17. Pull latest from Github master: `git pull origin master`
18. Delete local branch: `git branch -d BRANCH-NAME`

Aside: Make sure to move the issue from in-progress to review once the issue has been made a pull request. Also, move the issue to done once the pull request has been merged.