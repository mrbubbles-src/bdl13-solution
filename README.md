# bdl13-solution

# Branch Out

**Instructions**
* Create a new repository locally. 
* Add a readme file to the master branch. Add a heading to file. Make sure to add, commit your changes. 
* Create a branch named `content` and switch to the new branch.
* Add text to the readme file on the `content` branch. Don't forget to add and commit these changes.
* Go back to master and create another branch named `hotfix` from master. Note that the changes in your previous branch, `content`, are not there. 
* View all branches on terminal.

# Solution

```bash
cd Desktop
mkdir bdl13-solution
cd  bdl13-solution/
touch README.md
code .
```
README.md wird in VSCode editiert

### branch `content` wird erstellt

```bash
git add .
git commit -m "first commit"
git checkout -b content

```
### readme.txt wird erstellt und text in vs code hinzugefügt und geadded

```bash
touch readme.txt
git add .
git commit -m "first commit content branch"
```
