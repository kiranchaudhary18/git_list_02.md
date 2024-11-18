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
 