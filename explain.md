#### Task 1: Install and Configure Git

1.first install git from your window

2.your global git setting 
```
  git config -user.name "kiran"
  git config -user.email "kiran.chaudhary.cg@gmail.com"
  ```

3.verify the configuration
```
  git config --list
```
  
#### Task 2: Initialize a Repository  

1.first create a folder 
```
mkdir new_folder
cd new_folder
```
2.initilize a repository
```
  git init
```

#### Task 3: Creating and Committing Files

1.first create a file
```
   echo "hello" >text.file
```

2.add a file and commit
```
  git add .
  git commit -m "hi"
```
#### Task 4: Viewing Changes

1.modify the file 

  echo "my name is kiran" >text.file

2.check the file status and difference

  git status 
  git diff

#### Task 5: Undoing Changes  

1.unstage the staged file

  git reset text.file

2.discard uncommited changes

  git checkout -- text.file

#### Task 6: Branch Management

1.create a branch and switch 

 git checkout -b feature

2.list branches
 git branch

3.rename a branch
 git branch -m feature main  

 #### ask 7: Merging Branches

 1.merge the branch

   git checkout feature
   git merge main

#### Task 8: Handling Merge Conflicts
   