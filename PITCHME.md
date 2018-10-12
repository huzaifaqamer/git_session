# GIT 

An Introduction

---

### WHAT is GIT?

Distributed Version Control System

+++

### WHAT is a Version Control System?

- A system that keeps record of your changes
- Allows for collaborative development
- Allows you to know who made what changes and when
- Allows you to revert any changes and go back to a previous state

+++

### What is meant by GIT being Distributed VCS?

- Users keep entire code and history of project on their local machine
- Users can make modifications and snapshots of their work without internet access
- Only when code needs to be uploaded to or downloaded from remote server is internet access required

---

### When should we use GIT?

- A team is working on a project
- An individual is working on a project where history needs to be maintained

---?color=#f05033

# LET'S GIT AROUND

---

@snap[north-west]
GIT File Status Life Cycle
@snapend

@snap[west]
<br>
@ul
- **Ignored:** Files that satisfy .gitignore rules. These are ignored by GIT and cannot be tracked 
- **Untracked:** Newly created files which are not yet added to GIT tracking
- **Tracked:** Files that GIT is tracking for any modifications
@ulend
@snapend

+++

@snap[north-west]
GIT File Status Life Cycle
@snapend

@snap[west]
<br>
@ul
- **Unstaged:** Tracked files that have new modifications
- **Staged:** Tracked files that have new modifications on which 'git add' command has been executed
- **Committed:** Files on which 'git commit' command has been executed after they were staged
@ulend
@snapend

+++

![File Life Cycle](/img/git_file_life_cycle.png )

---

### Important GIT Commands

- *git clone:* Downloads GIT repository from remote server
- *git init:* Creates a GIT repository on local system
- *git status:* Shows current status of working directory
- *git log:* Shows list of commits i.e. history of repository
- *git add file:* Stage a file

+++

### Important GIT Commands

- *git reset HEAD file:* Unstage a file
- *git commit -m 'message':* Commit staged files
- *git checkout file:* Undo changes in a file
- *git pull:* Download changes from remote server
- *git push:* Upload local changes to remote server

---

### Difference between GIT and GITHUB

- GIT is a Version Control System tool
- GITHUB is a website where a GIT repository can be published
- Beside GITHUB there are other sites like GITLAB, BITBUCKET, etc.

---

# THANK YOU
