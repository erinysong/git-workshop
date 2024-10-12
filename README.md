# USDC Git workshop

Welcome to USDC's Git workshop repository! This workshop aims to teach the following:

- Learning outcome #1
- Learning outcome #2
- Learning outcome #3

Prerequisites for this workshop: 

Feel free to complete the activities in this repository at whatever own order and pace feels right for you. We have included instructions below for optional guidance.

## 1. Create your own fork of this repository
Create a fork of the git-workshop repository (which can also be referred to as a "repo") using the Fork button on the upper right corner of this repo page.

  <img width="1247" alt="image" src="https://github.com/user-attachments/assets/9d4a3231-e075-4459-8903-2e289f09cdb8">

In the owner dropdown, select your own GitHub username. You can keep the "Copy the main branch only" field checked.

  <img width="782" alt="image" src="https://github.com/user-attachments/assets/ae4e7f30-11e5-4436-982b-f8a59aef0034">

This creates your own personal copy of the git-workshop repo on your GitHub account. Your changes on your forked repo will only be reflected in your personal GitHub account's version of the git-workshop code. Think of it as making your own copy of a Google doc. Your changes on your created copy will not change the original Google doc you copied.

## 2. Create a commit and publish a change directly to the main branch
The goal here is to familiarize ourselves with the commit and push mechanisms. When you are finished making edits to a file, the next step is to "commit" your changes. You can think of a commit as a photo snapshot of this project at a specific point in time. You can always refer to previous "commits" in your project's git timeline if you need to refer back to specific changes. 

You can create as many commits as you'd like, but if you want to publish these commits to GitHub you the next step is to "push" your changes. You can think of pushing a change as having a Google doc stored locally on your computer. After you've made some changes and you want to share these with your team, you'd upload the Google doc to Google Drive where its hosted online for others to view.


### Update analysis_standards.md
Open the [analysis_standards.md](https://github.com/erinysong/git-workshop/blob/main/analysis_standards.md) file.

At the top right of the page you'll see a pencil icon, click it.

![Screenshot (256)](https://github.com/user-attachments/assets/b5077df6-fb39-4381-b229-1befc56b1ba7)

Instead of viewing the file you'll have options to either "edit" or "preview" the file.

Check that the "edit" tab is selected. Based on the sample data provided in the file, write down some recommendations on how you might perform data extraction, cleanup, validation, analysis, or presentation.

### Commit your changes to analysis_standards.md
After you've finished making your changes, click the "Commit changes..." button at the top right of the page. This will open up a modal with options for providing a commit message, an extended description, and buttons to either "Commit directly to the `main` branch" or "Create a **new branch** for this commit and start a pull request".

### Push your changes to main
In the commit message input, provide a short but descriptive message about your change. The extended description is optional. Ensure "Commit directly to the `main` branch" is selected then click the "Commit changes" button.

![Screenshot (258)](https://github.com/user-attachments/assets/5bfea91e-85e4-4a5f-a140-dc3555667b69)

## 3. Publish a change from a branch off main
In the previous exercise we practiced committing new changes and pushing them directly to the `main` branch. For many projects it is common to treat the `main` branch as the production version which is used by live users. As a result, it is best practice to not commit changes directly to the `main` branch as to not accidentaly introduce breaking changes.

To solve this problem, we can create our own branches and work on our changes there. This allows us to add new changes in an isolated environment which does not impact live users or other team members. 

### Create a new branch off main

To create a new branch on GitHub, we'll need to go back to the main page. If you're working from your forked repository, clicking the "Code" tab at the top of the page will take you here.

After doing so, you'll want to find and click the "1 branch" button.

![Screenshot (261)](https://github.com/user-attachments/assets/66d93fe2-fb09-404e-b2de-8107aba17a1e)

Next, you'll want to click the "New branch" button at the top right. This will open a modal with options for adding a "New branch name" and specifying a branch.

Set the branch name to anything you'd like. 
For the source branch:
- The first dropdown specifies which repository, keep this as the default which is set to your forked repository.
- The second dropdown specifies the source branch, or in other words the branch you're making a copy of. Keep this as the default which is set to the `main` branch.

Click the "Create new branch" button. 

![Screenshot (265)](https://github.com/user-attachments/assets/1fb4e340-c453-4596-96b6-5bf7de3e91ad)

### B. Update script.md

### C. Commit your changes to script.md

### D. Push your changes to your feature branch

## 4. Create a pull request from your change branch to main
