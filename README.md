# Git Branching Score Keeper

This exercise is intended to help practice git branching and merging using the CLI (terminal).

## Set-up

Start by selecting **Use this template** for this repository. Then **clone** the repository to your computer.

```
npm install
npm start
```

## Overview

Create a **new feature branch** for each of the tasks listed below and then merging the changes back into **main** using a **pull request** after each one. 

You will only be making changes to the **index.html** and **styles.css** files. 

**Don't over think this assignment. The focus is not on the tasks. The goal is to practice branching.**


## Task List

The client finally got back to us with answers to our questions. We can now make edits required to complete the Score Keeper website.

> **NOTE: COMPLETE THE TASKS IN ORDER & MERGE EACH BRANCH BACK INTO MAIN BEFORE DOING THE NEXT ONE**

### Base Mode

- [ ] **feature-team-names** - Team names have been assigned, they should read **Team Tomato** and **Team Plum**
   - After adding and committing, merge this branch back to `main`
- [ ] **feature-page-title** - The title of the page should read **Battle of the Fruits**
   - After adding and committing, merge this branch back to `main`
- [ ] **feature-bg-colors** - The team divs (with classes `.team1` & `.team2`) should have background colors that match the team names
   - After adding and committing, merge this branch back to `main`
- [ ] **feature-footer** - Create a footer at the bottom of the page that reads 'Made by Tomatoes inc.'
   - After adding and committing, merge this branch back to `main`

## Git Branching Cheatsheet

### Create a feature branch

- `git checkout main` - make sure you're on the main branch
- `git pull origin main` - make sure you're up to date
- `git branch feature-NAME` - Create a branch (replace **NAME** with your feature e.g. `feature-add-footer`)
- `git branch` - Display the branch you're currently on
- `git checkout feature-NAME` - Switch to the branch

### Commit one or more times

- `git add .`
- `git commit -m "MESSAGE"`
- `git push origin feature-NAME`

### Submit a pull request on GitHub

#### Step 1

![Step 1](/images/1_create_pr.png)

#### Step 2

![Step 2](/images/2_select_branch.png)

#### Step 3

![Step 3](/images/3_submit_pr.png)

> NOTE: You will only be able to approve the pull request (PR) if you selected "Use this template". If you forked the assignment, you won't have access to approve a PR.

#### Step 4

![Step 4](/images/4_merge_pr.png)

#### Step 5

![Step 5](/images/5_confirm.png)

That's it! Now repeat the steps for your next feature. Make sure to switch back to your `main` branch and pull down the updates.

- `git checkout main` - make sure you're on the main branch
- `git pull origin main` - make sure you're up to date

### Stretch Goals

- [ ] **feature-styling** - Add styling to make the page look better

### Additional Resources

- More Git practice: [https://try.github.io/levels/1/challenges/1](https://try.github.io/levels/1/challenges/1)
- Pull requests: [https://help.github.com/articles/creating-a-pull-request/](https://help.github.com/articles/creating-a-pull-request/)



