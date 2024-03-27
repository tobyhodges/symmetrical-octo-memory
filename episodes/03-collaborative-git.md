
---
title: Collaborative Version Control
teaching: 180
exercises: 2
---

:::::::::::::::::::::::::::::::::::::::: questions

- How can I use version control to collaborate with others?

::::::::::::::::::::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::::: objectives

- Understand the basics of collaborative version control with git and Github
- Understand the difference between centralized and distributed workflows

::::::::::::::::::::::::::::::::::::::::::::::::::

# Collaborative version control with git and Github

### Instructor notes
Teaching is done as a pair of instructors. 
Instructor A acts as the owner of the repository, instructor B as a collaborator (internal or external).

### Centralized workflow
First we show the centralized workflow all in the browser using Github: 

* instructor A creates an issue (for example create ‘sum’ function)
* instructor B picks up the issue  
* Instructor B creates a new branch (good to do this explicitly) 
* Instructor B does some reviewable changes (a simple ‘sum’ function) 
* Instructor B opens a new pull request. 
* Instructor A reviews and approves the PR. 
* Instructor B merges the pull request. 
* Use Github repo’s insights -> network to visualize what just happened 

::::::::::::::::::::::::::::::::::::::: challenge

### Exercise: Working as a project collaborator (in pairs):
#### Part 1
- PERSON A: Create an issue in the repository
- PERSON B: Clone this repository to your system
- PERSON B: Create a new branch
- PERSON B: Make the changes requested in the issue
- PERSON B: Push the changes to the remote repository on GitHub
- PERSON B: submit a Pull Request, refer to the issue (e.g. "Closes #1")
  
#### Part 2
- PERSON A: Review the Pull Request
- PERSON B: Address the comments
- PERSON A: Approve the Pull Request
- PERSON B: Merge the Pull Request
- (Optionally) Learn about [protecting branches](https://docs.github.com/en/github/administering-a-repository/about-protected-branches) and try it out. 

::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::: solution



::::::::::::::::::::::::::::::::::::::::::::::::::

### Distributed workflow
Second we show distributed workflow. All in the browser using Github:
* Instructor A removes instructor B
* Instructor B now submits an issue
* Instructor A responds to issue asking instructor B to pick it up
* Instructor B forks repo, does some changes, and submits PR
* Instructor A reviews the changes
* Instructor B implements the changes
* Instructor A merges the pull request
* Use Github repo’s insights -> network to visualize what just happened 

### Exercise: Working as an external contributor (in pairs)
#### Part 1
- PERSON A: Create an issue in Person B's repository
- PERSON A: Fork the repository to their own (= Person A's) account
- PERSON A: Clone the repository, make changes, push them back to the fork
- PERSON A: Submit a Pull Request from the fork to the original repository

#### Part 2
- PERSON B: Make a change in the original repository in the same place as person A's proposed changes
- PERSON A: Solve the merge conflict in the Pull Request
- PERSON B: Review/Approve the Pull Request
- PERSON B: merge the Pull Request
- 
### Key Points
* Git and Github are superpowerful, not just for version control, but as tools for collaborative development
* Do code reviews and be constructive in them!
* Use centralized flow for internal collaborations
* Use distributed flow for external collaborations

:::::::::::::::::::::::::::::::::::::::: keypoints

- Centralized workflow is good for internal collaborations
- Distributed workflow is good for external collaborations

::::::::::::::::::::::::::::::::::::::::::::::::::
