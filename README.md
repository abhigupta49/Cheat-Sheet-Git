
# Git Hub Commands

Git is the free and open source distributed version control system that's responsible for everything GitHub related that happens locally on your system.



## Setup

Configuring user information used across all local repositories.

```bash
  git config --global user.name "[firstname lastname]"
```
- set a name that is identifiable for credit when review version history
```bash
  git config --global user.email "[valid email]"
```
- set an email address that will be associated with each other marker

```bash
  git config --global color.ui auto
```
- set automatic command line coloring for Git for easy reviewing.

## Setup & Init



Configuring user information,initializing and cloning repositories

```bash
  git init
```
- initialize an existing directory as a Git repositories.
```bash
  git clone [url]
```
- retrieve an entire repositories from a hosted location via URL



## Stage & Snapshot


Working with snapshots and the Git staging area

```bash
  git status
```
- show modified files in working directory, staged for your next commit
```bash
  git add [file]
```
- add a file as it looks now to your next commit(stage)

```bash
  git reset [file]
```
- unstage a file while retaining the changes in working directory

```bash
  git diff
```
- diff of what is changed but no staged

```bash
  git diff --staged
```
- dif of what staged but not yet committed

```bash
  git commit -m "[message]"
```
- commit your staged content as a new commit snapshot

## Branch & Merge



isolating work in branches,changing context, and integration changes

```bash
  git branch
```
- list your branches. a* will appear next to the currently active branch
```bash
  git branch [branch-name]
```
- create a new branch at the current commit

```bash
  git checkout
```
- switch to another branch and check it out into your working directory

```bash
  git merge [branch]
```
- merge the specified branch's history into the current one

```bash
  git log
```
- show all commits in the current branch's history



## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/abhigupta49)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-kumar-6493861b1/)


