
---
title: Collaborative Version Control - Centralized
teaching: 50
exercises: 60
---

:::::::::::::::::::::::::::::::::::::::: questions

- How can I use version control to collaborate with internal collaborators?

::::::::::::::::::::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::::: objectives

- Understand the basics of collaborative version control with git and Github
- Understand the centralized workflow

::::::::::::::::::::::::::::::::::::::::::::::::::

::: instructor
Teaching is done as a pair of instructors. 
Instructor A acts as the owner of the repository, instructor B as a collaborator (internal or external).

First we show the centralized workflow all in the browser using Github: 

* instructor A creates an issue (for example create ‘sum’ function)
* instructor B picks up the issue  
* Instructor B creates a new branch (good to do this explicitly) 
* Instructor B does some reviewable changes (a simple ‘sum’ function) 
* Instructor B opens a new pull request. 
* Instructor A reviews and approves the PR. 
* Instructor B merges the pull request. 
* Use Github repo’s insights -> network to visualize what just happened 

:::

::::::::::::::::::::::::::::::::::::::: challenge

#### Exercise: Working as a project collaborator (in pairs):
- PERSON A: Create an issue in the repository
- PERSON B: Clone this repository to your system
- PERSON B: Create a new branch
- PERSON B: Make the changes requested in the issue
- PERSON B: Push the changes to the remote repository on GitHub
- PERSON B: Submit a Pull Request, refer to the issue (e.g. "Closes #1")
- PERSON A: Review the Pull Request
- PERSON B: Address the comments
- PERSON A: Approve the Pull Request
- PERSON B: Merge the Pull Request
::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::: solution

::::::::::::::::::::::::::::::::::::::::::::::::::


:::::::::::::::::::::::::::::::::::::::: keypoints
* Git and Github are superpowerful, not just for version control, but as tools for collaborative development
* Do code reviews and be constructive in them!
* Use centralized flow for internal collaborations
::::::::::::::::::::::::::::::::::::::::::::::::::
