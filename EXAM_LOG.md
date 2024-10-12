# EXAM LOG
## 1.
set up local git repository
created README.md file
created .gitignore file
created sample.java file
    git add sample.java
    git commit -m "Initial commit"

## 2.
git remote add origin https://github.com/ArvinGlenn-02/AGUID_REMOVAL_PRACTICAL_EXAM.git
git push origin main

## 3.
created feature-UI and feature-Backend branch
    git branch feature-UI
    git branch feature-Backend
created files for feature-UI and staged and committed the file with message
    git checkout feature-UI
    git add ui.html
    git commit -m "add ui.html"
created files for feature-Backend and staged and committed the file with message
    git checkout feature-Backend
    git add updated_sample.java
    git commit -m "add updated_sample.java file"

## 4.
merging the feature-UI and feature-Backend in the main branch
    git checkout main
    git pull origin main
    git merge feature-UI
    git merge feature-Backend
After merging the feature-Backend, I have encountered an error and fixed it
creating a tag
    git tag v1.0
    git push origin v1.0

## 5. 
Created CASE_ANALYSIS.md file
    git add CASE_ANALYSIS.md
    git commit -m "added the CASE_ANALYSIS.md file"

