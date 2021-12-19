# Team 78, Tutor Group 9 
Theme park website project

## Cloning the Repo

Download a git client
[https://git-scm.com/downloads/guis](https://git-scm.com/downloads/guis)

**To Clone this repo use**

> git clone https://_username_@github.com/umairaijaz86/t78_themeparksite.git

git will ask you to login to the repo, and clone everything for you


# Repo Process
  
## Branching
  Always branch to your own name from develop **never from Main**
  
  Main branch is for final consolidation and will remain empty till release.


### How to branch
  
> git checkout develop
> 
> git pull
> 
> git checkout -b _sectionname_

## Getting the latest work

> git checkout develop
> 
> git pull
> 
> git checkout _sectionname_
> 
> git merge develop

  so you are always working on the latest changes that are pushed by the team
  
## Committing

  When Commiting use the following as prefixes

* Feat: when addind something 
* Fix: when fixing an issue
* Chore: for anything else (comments etc)
  
  e.g. _Feat: Added a new section_
  
  e.g. _Fix: fixed a broken div_
  
  e.g. _Chore: added some html comments, removed unused attributes_
  
  commit often (use VS code it will help a lot)
  when you are done with your changes push.

## When pushing your changes
  
> git checkout develop
> 
> git pull
> 
> git checkout _taskname_
> 
> git merge develop
> 
> git push
  
  This will prevent any merge conflits and you will have the latest changes, run and check before pushing changes.

## When work is complete
  
  Once done with your end of the Task, we should create a pull request to develop
  so the code can be consolidated in the develop branch.

## For Questsions about the process, Merge conflicts
  
  contact Umair
