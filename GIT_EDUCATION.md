# Instruction to work with GIT
## 1. GIT INSTALLATION
### 1.1. To install GIT 
Download the last version from site [git download](https://git-scam.com/download). Install with default settings for your
### 1.2. To check if GIT is installed.
working in Terminal to execute command `git version`. In case installation is correct message with program version appears. Otherwise mistake message will appear.
### 1.3. GIT adjusting 
by starting to use GIT introduction is necessary. For that in terminal necessary to use command:
```
Git config —global user.name “your name”
Git config —global user.mail “mail@example.com”
```
## 2. Working with repository
### 2.1. Repository creation
Possible to get repository in 2 ways.
In terminal open the folder which is foreseen for Repository. Execute command:
```
Git init
```
GIT

#instruction to work with GIT



## 1. GIT INSTALLATION



### 1.1. To install GIT

Download the last version from site

[git download](https://git-scam.com/download)

Install with default settings.



### 1.2. To check if GIT is installed.

working in Terminal to execute command ‘git version’. In case installation is correct message with program version appears. Otherwise mistake message will appear.

### 1.3. GIT adjusting

By starting to use GIT introduction is necessary. For that in terminal necessary to use command:

‘’’

Git config —global user.name “your name”

Git confit —global user.mail “mail@example.com”

‘’’

## 2. Working with repository

### 2.1. Repository creation

Possible to get repository in 2 ways.

    1. In terminal open the folder which is foreseen for Repository. Execute command:
‘’’
Git init
‘’’
In initial folder hidden folder _.git_ will appear.
    2. To clone existing repository Git from any location. To do it as:
```
Git clone <repository address>
```
### 2.2. Making changes in repository 
each file in working folder can exist in one of two conditions: under version control (tracked) and not (untracked).git. Tracked files can be not changed, changed or prepared for commit.
- In order to see files status in repository execute command:
```
git status
```
- For new file tracking use the command:
```
git add <file name with extension>
```
- How GIT  changes use command:
```
git diff
```
You see in green only added lines and in red - deleted lines.

