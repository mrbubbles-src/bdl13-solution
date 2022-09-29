# bdl13-solution

# Branch Out

**Instructions**
* Create a new repository locally. 
* Add a readme file to the master branch. Add a heading to file. Make sure to add, commit your changes. 
* Create a branch named `content` and switch to the new branch.
* Add text to the readme file on the `content` branch. Don't forget to add and commit these changes.
* Go back to master and create another branch named `hotfix` from master. Note that the changes in your previous branch, `content`, are not there. 
* View all branches on terminal.

> check README files of other branches to see all solutions

# Solution

```bash
cd Desktop
mkdir bdl13-solution
cd  bdl13-solution/
touch README.md
code .
```
README.md wird in VSCode editiert

### main branch wird geadded und commited

```bash
git add .
git commit -m "first commit"

```

### branch `content` wird erstellt

```
git checkout -b content
```

### branch `hotfix`wird erstellt

```bash
git checkout -b hotfix
```