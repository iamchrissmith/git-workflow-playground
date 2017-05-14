Proper flow outline:

1. git add .
2. git commit -m "commit message"
    * if there are changes to pull, good practice to always check if we can pull from master
3. git checkout [main-branch]
4. git pull origin [main-branch]
5. git checkout [yourbranchname]
6. git merge [main-branch]
    * now we want to push our commits
7. git push origin [yourbranchname]

Start with roadshow:
* work on similar things to show merging from separate branches and simple merge conflicts
* demo bad merge conflict (refactoring code while someone is working on it)

Decrease conflicts and complications in the future especially around Pull Requests

Difference between `git fetch` and `git pull`

