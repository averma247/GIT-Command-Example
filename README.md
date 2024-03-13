#This is my remote repo
#This added from local


#GIT Commands list

Git commands. 


1. @averma247 ➜ /workspaces/MobileAutomationFwk (master) $ git stash
2. Saved working directory and index state WIP on master: 6e0c940 Added new code
3. @averma247 ➜ /workspaces/MobileAutomationFwk (master) $ git stash pop
4. @averma247 ➜ /workspaces/MobileAutomationFwk (master) $ git diff
5. diff --git a/README.md b/README.md
6. index a31afcd..592a2b5 100644
7. --- a/README.md
8. +++ b/README.md
9. @@ -1,2 +1,3 @@
10.  # MobileAutomationFwk
11.  this repo is created for Dummy Mobile AutomationFramework.
12. +This branch detials added but not to be commited.
13. \ No newline at end of file
14. @averma247 ➜ /workspaces/MobileAutomationFwk (dummy_ajBranch) $ git stash save "add: dummy stash code"
15. Saved working directory and index state On dummy_ajBranch: add: dummy stash code
16. @averma247 ➜ /workspaces/MobileAutomationFwk (dummy_ajBranch) $ git stash list
17. stash@{0}: On dummy_ajBranch: add: dummy stash code
18. @averma247 ➜ /workspaces/MobileAutomationFwk (dummy_ajBranch) $ git stash apply 0
19. On branch dummy_ajBranch
20. @averma247 ➜ /workspaces/MobileAutomationFwk (dummy_ajBranch) $ git reset
21. @averma247 ➜ /workspaces/MobileAutomationFwk (dummy_ajBranch) $ git add -p


