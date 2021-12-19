# Team 78, Tutor Group 9 
Theme park website project


## Cloning the Repo

Download a git client
[https://git-scm.com/downloads/guis](https://git-scm.com/downloads/guis)

**To Clone this repo use**

> git clone https://_username_@github.com/umairaijaz86/t78_themeparksite.git

git will ask you to login to the repo, and clone everything for you


# Repo Process
  
  When starting a task go to the project board 

  https://github.com/umairaijaz86/t78_themeparksite/projects/1

  and move your task to in progress.

## Branching
  Always branch to your own name from **Main**

### **How to branch**
  
> git checkout main
> 
> git pull
> 
> git checkout -b _taskname_

_note: for the branch names the taskname and section name are the same name, so when someone is working on the **index banner** the task name will be called **indexBanner** and the branch name will there for be **indexBanner**_

## Getting the latest work (getting the latest changes)

> git checkout main
> 
> git pull
> 
> git checkout _taskname_
> 
> git merge main

  so you are always working on the latest changes that are pushed by the team
  
## Committing changes (this does not sync online)

  When Commiting use the following as prefixes

* Feat: when addind something 
* Fix: when fixing an issue
* Chore: for anything else (comments etc)
  
  e.g. _Feat: Added a new section_
  
  e.g. _Fix: fixed a broken div_
  
  e.g. _Chore: added some html comments, removed unused attributes_
  
  commit often (use VS code it will help a lot)
  when you are done with your changes push.

> git add .   //adds the current directory for committing
>
> git commit -m ' write down what you are committing'
>

## When pushing your changes

only push the stable branches when you have something that works ( this helps with roll backs ) when something is broken

### **First time push**

!! When pushing for the first time, Git will ask you to setup the up stream and provide you with the command to use, 
 
  The To set    
  
  > git push --set--upstream origin _taskname_
 
  this will create a corrosponding branch on the git repo and allow you to push to it

### **All other times**
  
> git checkout main
> 
> git pull
> 
> git checkout _taskname_
> 
> git merge main
> 
> git push
  
  This will prevent any merge conflits and you will have the latest changes, run and check before pushing changes.
 
## When work is complete
  
  Once done with your end of the Task, we should create a pull request to main

### **Creating the Pull request**

  When creating the pull request (pr) please make sure 

  1. the pull request has the same name as the task (for readibility)
  2. the Pull request is from your branch to **main**
  3. <p>the comment contains a closing comment (this helps automate the board)<p><p>so for task #4 the closing comment will be  ' closes #4 '<p>
  4. assing the reviwer andd assignee
  5. assigned the corret project
  6. create the pull request

### **when reviewing the pull request**

  1. Pick the pull request from the board
  2. review the code and make sure its up to standard and all requirement sfrom the task were fulfilled
  3. Leave a comment (request change) or
  4. Confirm the changes and approve the Pull request
  5. Merge the branch 

_when in doubt checkout the branch on your local machine and run it_

so the code can be consolidated in the main branch.

### **In case of merge conflicts**
<p>

***TBD***

</p>

## For Questsions about the process, Merge conflicts etc
  
  contact Umair
