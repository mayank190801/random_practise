# random_practise
Just for practising random merging and branching techniques for git in free time

first change in main branch

making changes and doing a push requests

Basically all the branches when you clone a repo are present -
    git branch -a to view them

ofc if a branch is there, then you would need a tracking local branch
    git switch feature/232

The above command should automatically create a branch with same name to track it 
    git switch -C mayank/232 feature/232 would be there no worries

You can create a new branch and switch from here
    git branch mayank/newbranch
    git switch mayank/newbranch

Make your changes and commits, since this is a new local branch, if you want it to show on github repository you have to push it with upstream
    git push --set-upstream origin mayank/newbranch 

This would push the branch to github repository bro and will do your thing for sure
    git log --oneline --all --graph

Use the above command for visualising it properly