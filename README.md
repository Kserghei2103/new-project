      Instructions.

1. Creating a new repository 

Сreate a new directory named "new-project" in your environment:
mkdir new-project

Navigate to the "new-project" directory:
cd new-project

Initialize a new public Git repository inside the "new-project" directory:
git init

Rename the default branch to 'main' if it has a different name:
git branch -m main 

2. Creating a new branch

Сreate a new branch named "development" and switch to it:
git checkout -b development

3. Merge changes from the "development" branch into the "main" branch

Switch to the "main" branch:
git checkout main

Merge changes from the "development" branch into the "main" branch:
git merge development

Сheck the status and ensure everything is up to dateЄ:
git status