# Git_CheatSheet

## For complete git commands check the online documentation
[online documentation] (https://git-scm.com/docs)

### Set Up Repository Commands
1. Set Up Terminal / Bash Commands
```
echo "# Git_CheatSheet" >> README.md
git init
git add README.md
git commit -m "<Commit Message>"
git branch -M main
git remote add origin <Repository Link>
git push -u origin main
```
2. Pushing Files Terminal / Bash Commands
```
git remote add origin <Repository Link>
git branch -M main
git push -u origin main
```

3. Make a copy of the repository in your local machine (be sure to go to your chosen folder first)
```
git clone
```

### How to Contribute
1. Create a New Branch

```
git checkout -b <Branch Name>
```
2.  Apply changes to the code 
3.  Save the changes
```
git add .
```
5. Commit Changes 
```
git commit -m "Add Details"
```
4. Push  the changes
```
git push origin -u <Branch Name>
```
5. Go to repository
6. Create a Pull Request then submit
7. If there are no conflicts click merge changes

### How to Update Local Machine If Repository Is Changed

1. Switch to the Main Branch
```
git checkout main
```
2. If you can't switch branches stash your current branch
```
git stash
git checkout main
```
3. Pull Repository Changes
```
git pull
```
4. Checkout to your current branch
```
git checkout <Branch Name>
```
5. Rebase your current Branch
```
git rebase main
```
6. If you stash your current Branch 
```
git stash pop
```
7. Double-check if your current branch contains the changes from the main branch
