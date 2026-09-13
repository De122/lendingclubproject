git branch - to chec which branch 
git branch -m main - to rename a branch 
git branch feature1 - to create a new branch (here, feature1)
git checkout feature1 - to switch to a branch (here, feature1) 

3 (create) and 4(switch) are two steps to move to a branch

To do both 3 & 4 in one step, we do - git checkout -b feature2 

NOTE :- Whichever branch we are currently in, its code is taken up by the new branch that we create whether it is using the two steps (3 and 4) or using step 8. 
Another way to do so is -> git checkout -b feature2 feature3 

To delete a particular branch (let say, feature2) we need to be on a different branch (let say, feature1 or main) -> git branch -d feature2 (currently, on main)
