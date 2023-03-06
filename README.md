![alt Github image](images/GitHub.jpg)
<!-- # Git-GitHub-GitHubClassroom -->
# Introduction: Git and GitHub
## 1. Installing Git
First, we need to install Git: the version control software.
- Git:
  Install [git](https://git-scm.com/downloads)

## 2. Configuring Git Account
Open a terminal on your Windows or Mac and then write the following commands:
![alt Github image](images/config.svg)

## 3. Initialize a Local Repository
1. First, let's start by creating a folder for our project. For this you can use the GUI of Windows or Mac, use a terminal or your preferred IDE.
2. Next, cd into your project folder: 
```shell
cd project_name
```
3. Finally, we need to initialize the repository using the following command:

```shell
git init
```
![alt Github image](images/Git%20init.png)


## 4. Staging & Tracking Files

### 4.1. Adding files to the staging area
1. Create a file named _index.html_ containing a simple _\<h1> tag_
2. Git does not know about the file _index.html_. We can check the tracked files using the following command:

```shell
git status
```
3. The git status command allows you to know the status of the project: If it is initiated, modified, staged
![alt Github image](images/Git%20Status.png)

3. For Git to recognize this file, we need to add it to the staging area and create a commit. <br>
There are multiple ways to add files to the staging area. <br>
- Add a single file
```shell
   git add filename
```
- Add multiple files
```shell
   git add filename1 filename2
```
- Add multiple files and folders at once. Make sure to add a space between the add and the dot.
```shell
   git add .
```

![alt Github image](images/Git%20track.png)


4. To remove a file from the staging area, we need to use the following command:
```shell
    git rm --cached filename
```

### 4.2. Commits
A commit allows us to create a snapshot of the project state at that point of time. To create a commit, we use the following command with _-m_ stands for message and we list the message associated with this commit. 

```shell
   git commit -m 'your message'
```
The message should be short and accurately describes the changes made. A clear message would allow us to identify a specific commit and eventually roll back to that state if needed.

![alt Github image](images/Git%20Commit.png)

## 5. Branches
<!-- # Basic Command Lines -->
