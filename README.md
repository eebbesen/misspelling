# misspelling
A repo used for your first GitHub commit.

## Prerequisites
* Install Git (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* Create a GitHub account (https://github.com/)

### Helpful but not mandatory
* See how much this confuses you: https://www.atlassian.com/git/tutorials/comparing-workflows
* Take https://guides.github.com/activities/hello-world/ -- it is better than this project at getting you going with Git

## How to use this repo
This project contains mispelling.txt which has many commonly misspelled words. And is itself misspelled!

You can use it any way you want, but one way is to
1. Fork the repo
1. Clone your fork
1. Create a branch
1. Make a change
1. Commit that change
1. Push that change
1. Open a pull request

### Fork the repo
Forking a repo gives you a copy you can use to develop. You can use the fork to submit fixes to the forked repo, but in many cases you may never do so. Even if the forked repo doesn't want your changes, your changes can live a full life on your fork!

To fork this repo click the Fork button below the top ribbon and to the right.

https://help.github.com/en/articles/fork-a-repo

### Clone your fork
This is how you'll get the fork from GitHub to your local computer. You can edit most files directly via a browser on GitHub if you'd really rather. There's a button Clone or download that will give you more options. Click Use HTTPS if you have issues with SSH. Here's what will likely work:

`git clone https://github.com/eebbesen/misspelling.git`

### Create a branch
This further isolates your workspace so that you can avoid problems with merging, and to make presenting your changes to others easier.
`git checkout -b my_new_branch`

### Make a change
Find a misspelling and fix it! Try to pick one your peers haven't taken care of already. Don't forget to save your changes!

### Commit that change
Make that change permanent(ish) and shareable.
`git add .`
`git commit -m 'fixing a misspelling'`

### Push that change
Back to the cloud we go!

`git push origin my_new_branch`

https://help.github.com/en/articles/pushing-to-a-remote

### Open a pull request
