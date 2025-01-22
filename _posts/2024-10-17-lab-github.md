---
title: 'Start a GitHub repository for your lab'
date: 2024-10-17
permalink: /posts/2024/10/lab-github/
tags:
  - Open source
  - Open access
  - GitHub
  - Lab Management
  - Code
  - Protocol
  - Standadize
---

Collaborative coding is an essential part of everyday practices in an academic lab. Although there is a learning curve to get to use code mangement plateforms (like GitHub) for non-CS researchers, it will greatly accelerate the coding process and benefit the whole lab once you get it running. 

### Get to know GitHub

GitHub is one of the most popular code management plateforms for software developers around the world. 
There are many useful features, and now even better with Copilot. Academic labs get to take advantage of educational benefits to upgrade to GitHub Pro for free.

**GitHub is not intended for large file storage (>25 Mb).** Unless your experimental data file is small, don't try to store your raw data files on GitHub. But you can store exported data or analyzed data results. 

### Design the Repository Structure 

You can created unlimited repositories. It is important to create a structure system to keep things organized and well-tracked as the number of repositories grow. 
Create an organization account as PI, and add all lab members to the organization. 

### Manage account safety

To keep organization account safe, set strong password and enable two-factor authentication for Admin user and all members.
To keep the repositories safe, only grant admin rights to selected members that are cautious and more knowledgeable about the GitHub. 

### Migrating your legacy code 

You might have many old code files and some code version actively using. Upload everything, commit, organize and update as you make more commits. Since all the commit history are saved, you don't need to worry about losing anything. Your repositories might be ugly and chaotic at first, but it will get better over time, as are the codes from software developers. To make it easy on yourself, do take a few second to write the commit message to remind the future you why you are making a certain commit. 

### Cultivate the habit of using GitHub

Using GitHub might appear as an daunting task and unnecessary effort at first for people who can't see the benefit of using it or reluctant with the learning curve. You can only see the benefit after you pass the learning curve and start using it. Someone has to head spear the process and demonstrate how it works in the collaborative coding process. 

### Publish and reference your code

It's common to reference the code repository at the end of the publication, section **data availability**. 

## Note about academic coding

Many researchers from non-engineering or non-CS background do not have enough training or experience in programming. They may be able to write some rough code to perform data analysis and statistics, but they usually don't know the best practices in collaborative coding, or have the habit of code version management.

Here are some common examples: 1. Write all code in the same script without using helper functions. 2. Rename your code with a date or version appendix instead of using a proper version control system like Git. 3. Store your code on a cloud drive like Google Drive or Onedrive instead of using a code management plateform like GitHub.

**The common goal of coding for many researchers, is to perform a certain type of experiment or data analysis, rather than building a robust and easy-to-use software. That is, to get it working rather than get it pretty.** While it might greatly benefit the research community to publish your code, it usually takes a lot of additional effort to turn your scaffold code into an easy-to-use code package that will work robustly outside your computer. For example, you need enough code annotation for readability, documentation to help demonstrate how to use your code, generalize the function to accept more formats of input, supporting functions to help debug, commit time to answer questions from other researcher. 

Analogy: making a commercial software is like constructing a building. **Dig foundation -> make scaffold -> build load-bearing structure -> exterior finish (wall & roof) -> plumbing and wiring -> interior finish -> decoration**. While a commercial software would go all the way to the last step, most researchers would stop at the second or the third step. **If it works, it is enough.** Unless computing resources are limited, no one would even try to optimize the code runtime.