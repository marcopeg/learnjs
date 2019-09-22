# Introduction to Git and GitHub
[LearnJS](../../README.md) » [Git](./README.md)

**===========================================================**  
**THIS PAGE IS A DRAFT AND MAY BE SUBJECT TO A LOT OF CHANGES**  
**===========================================================**  

The goal of this roadmap is to familiazie with Git and GitHub.

At the end of it, you will have your personal website published
using a free hosting service offered by GitHub and called GitPages.

Here are plenty of video tutorials:  
https://www.youtube.com/user/GitHubGuides

## Part 1 - The Setup

#### Verify you have `git` available to your computer

[Git for Windows](https://gitforwindows.org/)

{% youtube embed="7Inc0G0wutk" %}{% endyoutube %}

#### Initialize a new Git project on your computer

{% youtube embed="FyfwLX4HAxM" %}{% endyoutube %}

(don't bother with the "add remote" part of this video!)

## Part 2 - Work Locally

#### Create an `index.html` with some markup inside

Spend 2 more minutes and add your picture to the same folder,
so that you can show it in your page :-)

#### Create your first _commit_

{% youtube embed="A-Cll9jEnnM" %}{% endyoutube %}

make sure you play around with `git status` and understand how to
read the results.

#### Add more files, then _commit_ again

See if you can add a secondary page where you will write your
experience, and link it to the `index.html`

#### Check out your commit history with `log`

{% youtube embed="Ew8HQsFyVHo" %}{% endyoutube %}

- What is the order that is used while showing multiple commits?
- How do you find out how did a specific commit?

#### Add more commits

... as your website grows ...

## Part 3 - GitHub & Online Persistency

#### Create an account on GitHub

#### Setup your computer with `ssh` access

https://help.github.com/en/articles/testing-your-ssh-connection

Why is SSH better than HTTP for GitHub (also GitLab and BitBucket)?

#### Create a new repository with a README.md in it

#### Use the GitHub UI to play with files

- edit `README.md`
- create a new file
- do commits

Questions:

- Notice how GitHub automatically renders the `README.md`? 
- What is the _Markdown_ language?
- Why is so important to write readme files?

#### Clone your repository to your computer

#### Make a local commit, then `push` it to the GitHub repo

#### Make a commit with GitHub UI, then `pull` it to your local repo

## Part 4 - GitPages: enjoy free hosting!

#### Create the GitPages repo for your account

name it `{account-name}.github.io` and **do not** choose to add a
`README.md` to it.

- Do you see all the instructions how to setup a local repo with
the newly created GitHub one?

#### Setup a `remote` for your website repo

Use the instructions from your empty repo to **create the connection**
between your local repositiory and the GitHub's one.

Make sure you push all your commits to the online repo.

- How do you make sure the two repos are aligned?

#### Setup GitPages for your repository

tip: it's in the "settings" tab of your repo

- What is the url of your personal website?

## Part 5 - Branching & Pull Requests

- what is a "branch"?
- why are branches useful to code collaborations?

#### Create a local branch

{% youtube embed="HwrPhOp6-aM" %}{% endyoutube %}

- make some changes
- commit

#### Switch between branches

- can you change branch if there are open changes? 
- can you go back in time?

#### Revert a wrong change

#### Push your branch to GitHub

#### Use GitHub to navigate between branches

#### Use GitHub to create a Pull Request

{% youtube embed="d5wpJ5VimSU" %}{% endyoutube %}

Play around with comments, new commits, take a look at the PR
history.

Try to play with both merge and rejected pull requests.

Try to go around GitHub and look at PullRequests of famous repositories
like [React](https://github.com/facebook/react) or
[Svelte](https://github.com/sveltejs/svelte)

## Part 6 - Code Collaborations with GitHub

{% youtube embed="aJnFGMclhU8" %}{% endyoutube %}

#### Invite a friend as collaborator to your repo

#### Use GitHub issues to document what needs to be done

Take also a look at GitHub Projects!

#### Reference issues in your commits

Take a look at the issue page and notice how the history will
automatically display every linked commits.

#### Open Pull Requests

- try to be picky and add comments to the PR's changes
- also, ask the author of the PR to change something

try to have multiple running PRs, practice in checking them out locally
to that you - the project's owner - can test and accept them.

## Part 7 - Open Source Collaboration

> The best way to try this is to play with a fellow studend using repos
> from two different accounts!

{% youtube embed="yr6IzOGoMsQ" %}{% endyoutube %}

#### Fork an existing Repo

#### Setup the `upstream` origin

#### Try to pull new changes from the upstream

#### Create a branch and commit some changes

#### Create a PR to the original repository







