# Instruction to work with GIT
## 1. GIT INSTALLATION
### 1.1. To install GIT 
download the last version from site [git download](https://git-scam.com/download). Install with default settings for your
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
possible to get repository in 2 ways.
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
### 2.3. Text formatting 
there are particular syntaxes rules which help to make the text more readable. Examples: **bold**, *intalics*, ~~strike through~~.
### 2.4. Lists formatting 
lists can be numbered and not numbered. Numbered lists start with number like `1. List 1`, not numbered lists start with `+`, `-` or `*`.
### 2.5. Saving changes
It is strongly recommended to save all changes on the continuous basis. For that add message reflecting the respective change and commit with the command as:
```
git commit -m “added xxx message”
```
second option for saving changes is:
```
Git commit -am “added xx message”
```
### 2.6. To switch between changes 
to switch Between changes execute command: `Git checkout ‘name change from log’`.
### 2.7. Commit history review
For making history review to see detailed list of changes use command:
```
Git log
```

for the brief list of changes execute command:
```
Git log —oneline
```
### 2.8. To insert quotes

To insert quotes you have to add text as <text. Example: *< кто не работает, тот не ест*.

To insert quotes in quote insert text with indent:

> first level of quoting
>> Second level of quoting
>>> Third level of quoting
>
> first level of quoting

![hard work](Programmer.jpg)
### 2.8. To insert quotes
>Sweet are the uses of adversity which, like the toad, ugly and venomous, wears yet a precious jewel in his head.
### 2.8. To insert quotes
>Sweet are the uses of adversity which, like the toad, ugly and venomous, wears yet a precious jewel in his head.git
## 3. To create branch
In order to craete branch you have to use command *git branch branch.name"
```
git branch name
```
to switch to branh use command
```
git checkout name
```
# 4. Merge branches
# 5. Graph
to see history use *git log --graph*
# 6. Work with remote repositry
1. To create account at GITHUB
2. To create local repositry and create copy of other repositiry with icon 'fork'
3. To create request to combime ocal repositry with remote
