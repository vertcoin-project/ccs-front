---
layout: post
title: How to submit a CCS proposal.
---

#### Note: Read the [What is the CCS and What Are Its Rules and Expectations](/what-is-ccs) page before continuing!

The CCS utilizes Github for proposal tracking. A quickstart guide is provided at the top for those already well-versed GitHub and step-by-step instructions (with pictures) are provided afterward for those who need help getting through the process. An example proposal is provided at the bottom of this document for referential purposes.

## Table of Contents
- [Quickstart Guide](#quickstart-guide)
- [Step-by-step Instructions](#step-by-step-instructions)
- [Example Proposal](#example-proposal-front-matter)
- [Editing or Amending a Proposal](#editing-or-amending-a-proposal)

## Quickstart Guide
1. Register for an account on [Github](https://github.com) and fork the [CCS Proposals repository](https://github.com/vertcoin-project/ccs-proposals)
2. Make a new branch, named similarly to your proposal
3. Add a new `.md` document, and title it similarly to the title of your proposal with your name or handle in the file name.
4. Use the template provided below for the front matter, and place it at the top of your proposal. You are responsible for adding the appropriate amount of milestones, with an equal number of payouts below the milestones. FORMATTING MUST BE PRESERVED, OR THE PROPOSAL WILL NOT WORK! Do NOT fill in the `done:` variable under `milestones:`, and do NOT fill in anything under `payouts:` besides making sure the number matches the number of milestones.

```
---
layout: fr
title:
author:
date:
amount:
milestones:
  - name:
    funds:
    done:
    status: unfinished
  - name:
    funds:
    done:
    status: unfinished
payouts:
  - date:
    amount:
  - date:
    amount:
---
```

5. Underneath the front matter, write the rest of your proposal. Be sure to include what the proposal is about, who will be completing it, why it is important for the community, the milestones and projected timeline, and an expiration date for your proposal.
6. Save, commit, and make a Pull Request to the repo. Your PR title must be descriptive and relevant to your proposal. The PR description should be copy/pasted from the proposal contents for easy viewing (front matter excluded).
7. You're done. Go start letting people know about your proposal.

## Step-by-step Instructions

### 1. Github

**You will only have to do this step once! If you make future proposals, you can skip to Step 2.**

First things first, you're going to need an account on [Github](https://github.com). Register for an account (use a strong password), and then navigate to the [CCS Proposals repo](https://github.com/vertcoin-project/ccs-proposals). **Click the 'Fork' button.**

![Click this fork button](/img/how-to/fork.png)

When completed, you should see the repository under your username, indicating a successful fork.

### 2. Branches

Creating a branch for your work is a common and recommended practice for users of Github. This also makes the maintainer's lives a lot simpler.

Click on Branch: **master** ![Click on Branches](/img/how-to/branches.png) Enter the name of your new branch in the dialogue box, then click on **Create branch:**. The new branch name should be something similar to your proposal. No spaces are allowed. ![Click on New Branch.](/img/how-to/new-branch.png) You should be taken back to your repository, but now on the new branch, as evidenced by seeing the name of your new branch on the screen. ![Hooray! You're on your new branch.](/img/how-to/new-branch-success.png)

### 3. Make the proposal file

From here, you're going to click **'Add file'** and then **'Create new file'** in your new proposal branch. ![Plus button](/img/how-to/new-file.png) On this new screen, fill in the 'Name your file...' field with your name and a descriptive title that is relevant to your proposal.  The file name must end in `.md`. As an example, if Bob was to make a proposal asking for funding to make upgrades to OCM they might title the file `bob-upgrades-to-ocm.md`.


### 4. Front matter

Before you begin writing your proposal, you must copy the following template and paste it onto the top of your file:

```
---
layout: fr
title:
author:
date:
amount:
milestones:
  - name:
    funds:
    done:
    status: unfinished
  - name:
    funds:
    done:
    status: unfinished
payouts:
  - date:
    amount:
  - date:
    amount:
---
```

Fill this template out as follows:

`layout:` Do NOT touch this field.

`title:` Fill this in with your name and a descriptive title of what your proposal wants to accomplish.

`author:` Put your name or handle here.

`date:` Put the date you are proposing and submitting this to the community in the following format: `October 17, 2021`.

`amount:` Put the amount of Vertcoin you are requesting to complete this.

`milestones:` Do not put anything after Milestones directly, but rather the fields that follow it. Copy and paste from one dash (`-`) to the other, depending on how many milestones your proposal will take. If you have four milestones, you should see put the following:

```
milestones:
  - name:
    funds:
    done:
    status: unfinished
  - name:
    funds:
    done:
    status: unfinished
  - name:
    funds:
    done:
    status: unfinished
  - name:
    funds:
    done:
    status: unfinished
```

**EXACT FORMATTING MUST BE PRESERVED WITH THE SPACING OR THE PROPOSAL WILL NOT WORK.** It's the way Jekyll (on which this is built) functions. The dashes must be two spaces from the left margin.

Fill in the `name:` field with the name of the Milestone (for example: Complete Video 1), and the `funds:` field with the amount of Vertcoin you expect to receive for completing the milestones. Do not touch the `done:` or `status:` fields. Repeat until all the `name:` and `funds:` fields are filled in. At the end of this page is an example.

`payouts:` Copy and paste the same amount of variables under payouts that you have under milestones. If you have three milestones, you should have three sets of `date:` and `amount:` variables underneath `payouts:`. Do not fill in these fields.

### 5. Writing your proposal

NOW you can put your proposal beneath the front matter (underneath the last three dashes). When writing the proposal remember to include:

- What the proposal is about.
- Who will complete the proposal?
- Why it is important for Vertcoin and the community.
- Your milestones and projected timeline
- An expiration date for the proposal. If it's not funded or finished by a certain time, the funds can be released to other proposals or the General Fund.. This keeps things moving along in a timely fashion.

After all of this is done, click the green **'Commit new file'** button at the bottom. ![Example proposal file](/img/how-to/proposal-example.png)

### 6. Make a Pull Request

After you click 'Commit new file', you will be taken to your branch where you can see the newly created file. You should also see a **'Compare & pull request'** button. Click on it to start the pull request.

 ![File creation success and pull request button](/img/how-to/pull-request.png)

In the Title field, put the same title that you used in the front matter of your proposal. In the 'Leave a comment' text box, paste in the proposal EXACTLY AS IT APPEARS IN YOUR .md file, minus the front matter. ![Fill in title and description fields](/img/how-to/create-pull-request.png)

After this is done, scroll down, and click the green **'Create pull request'** button at the bottom left of the page. You should be taken to the Pull Request page for your proposal.

### 7. You're done. Now go drum up some support.

Good job on getting all the way here. When you finish, the community will be discussing your proposal on the pull request itself. If you want to weigh in on the discussion, feel free. It will be up to you to get people to support your proposal, both for it to be moved to the Funding Required stage, and also while its awaiting donations. Best of luck, and thank you so much for contributing to Vertcoin. We, the community, really appreciate it.

## Example Proposal Front Matter

```
---
layout: fr
title: Upgrades to OCM
author: Bob
date: October 17, 2021
amount: 10000
milestones:
  - name: Milestone 1 - Backend work
    funds: 50% (5000 VTC)
    done:
    status: unfinished
  - name: Milestone 2 - Frontend work
    funds: 50% (5000 VTC)
    done:
    status: unfinished
payouts:
  - date:
    amount:
  - date:
    amount:
  - date:
    amount:
---
Proposal details written here.
```

## Editing or Amending a Proposal

Often times through community critique and feedback, it is necessary to edit a proposal after the Pull Request has already been submitted. This can be done in the following way:

### Navigate to your CCS Proposals repository

Find your copy of `CSS Proposals` in your repositories and click on it.

### Branches and files

Locate the dropdown with all of your active branches and select the branch on which your proposal was made. ![Branches dropdown](/img/how-to/find-branch.png)

### Editing the file

Open your file and in the upper right corner should be an Edit button. ![Edit button](/img/how-to/edit-button.png) Select this and you should be taken to the editing screen. Amend the proposal as needed (remember to edit the front matter too if any of those variables are changing) and press the green 'Commit Changes' button at the bottom.

**Warning! Not only the changes but THE FACT that you made changes will be visible to EVERYONE! You CANNOT stealth edit your proposal.**
