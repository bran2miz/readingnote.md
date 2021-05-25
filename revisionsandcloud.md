# Revision and the Cloud

### Types of Version Control Systems (VCS)

There are three types of version control systems that developers use for managing and storing data. 

1. **Local Verson Control**
        - older system with a single database that  saves all of one's files. 

2. **Centralized Version Control (CVCS)**
        - System in which one server saves all file modifications.
        - Easily accessible to collaborative developers
        - Collaborative involvement of developers within a project.

3. **Distributived Version Control (DVCS)**
        - Alliviates the major issues and problems that can happen with using CVCS
        - I.e. The CVCS shuts down, gets hacked or corrupted.
                - DVCS has a backup plan: the developer possesses through DVCS multiple copies of repositories (a collection of files and folders) in case all the data is lost.

### So what is Git?

**Git** is a version of DVCS that holds a system within it also known as *snapshot*.
    - It is essentially an identical process of saving files like you would with a document on a computer.
    - This saving process in git is called *commit*.
    - However, unlike an application like, Microsoft Word, a developer using git is able to bring up previous version of the file, and modify them however they see fit.

### History of Git

The origin of Git began when developers used a program called BitKeeper, established in 2002. However, many software developers apparently stopped using all forms of DVCS mainly because of brewing rivalry betweent BitKeeper and the DCVS based Linux kernel. Eventually, a man named Linus Torvald (the chief architect at Linux kernel) developed what we know today at **git**.
    - The birth of git now allowed developers the ability to create "branches" from the original git track.
        - Promoted the creation of detailed coding and endless possibilities. 

### Code configurations

#### Identity setting

For personalization or a "signature"

> git config --global user.name "Brandon Mizutani"
> git config --global user.email "bran2miz@gmail.com"
    
To double check to make sure that the settings are acceptable:

> git config --global user.name
> git config --global user.email

#### Default Text Editor

    git config --global core.editor emacs

#### Check Settings

    git config --list

    git help command - Essentially it enables the user to "get" help to get more information. 

#### ACP

git clone - addes an existing URL from an already existing repository

> ie-  git clone https://github.com/test

#### **ACP is an acronym for Add, Commit, and Push.**

##### Add file

> git add "README.md"

##### Commit

commit- saving the added file and storing it.
     - commit messages can be added for other developers within your team to see the changes that were made. 

> git commit -m "made specific changes on a,b,c"

To save all files 

> git commit -a

##### Push

Push sends the new changes from the file to the online git repository.

> git push origin main

##### Stash

Stash- allows a user that is on the verge of "committing" their file but also wants to save their changes.
    - Temporarily hides changes.

> git stash

To obtain the original changes:

> git stash apply

[<== Back](README.md)