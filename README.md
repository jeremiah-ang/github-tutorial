# github-tutorial

A dummy tutorial for people to practice the workflow of github

# Basic set up practice

```bash

# Firstly fork the original repository if you have not done so.

# Create a copy of the repository on your local computer
git clone https://github.com/<YOUR_GIT_USERNAME>/github-tutorial

# Go to the folder
cd github-tutorial

# Make some changes; replace <YOUR_NAME> with your own name.
# e.g. echo "jeremiah-ang" >> names.txt
echo "<YOUR_NAME>" >> names.txt

# Stage the file (i.e. select files to create commit with)
git add names.txt

# Create a commit; similarly, replace <YOUR_NAME> with your own name.
git commit -m "add <YOUR_NAME> to names.txt"

# Push to repository
git push -u origin master
```

# Branching Practice

```bash

# Firstly fork the original repository if you have not done so.

# Create a copy of the repository on your local computer
git clone https://github.com/<YOUR_GIT_USERNAME>/github-tutorial

# Go to the folder
cd github-tutorial

# 2 in 1 command: Create a branch and checkout to it, replace <YOUR_NAME> with your own name
# e.g. git checkout -b jeremiah-ang
git checkout -b <YOUR_NAME>

# Make some changes; replace <YOUR_NAME> with your own name.
# e.g. echo "jeremiah-ang" >> names.txt
echo "<YOUR_NAME>" >> names.txt

# Stage the file (i.e. select files to create commit with)
git add names.txt

# Create a commit; similarly, replace <YOUR_NAME> with your own name.
git commit -m "add <YOUR_NAME> to names.txt"

# Go back to master branch
git checkout master

# You can now verify that your name is missing from the names.txt

# Merge your branch to master
# e.g. git merge jeremiah-ang
git merge <YOUR_NAME>

# Push to github
git push
```
