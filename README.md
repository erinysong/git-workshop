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

Next, you'll want to click the "New branch" button at the top right. This will open a modal with options for adding a "New branch name" and specifying the source of a branch.

Set the branch name to anything you'd like. 
For the source branch:
- The first dropdown specifies which repository, keep this as the default which is set to your forked repository.
- The second dropdown specifies the source branch, or in other words the branch you're making a copy of. Keep this as the default which is set to the `main` branch.

Click the "Create new branch" button. 

![Screenshot (265)](https://github.com/user-attachments/assets/1fb4e340-c453-4596-96b6-5bf7de3e91ad)

Under "Your branches", you should now see the new branch. 
![Screenshot (267)](https://github.com/user-attachments/assets/7e28e184-373f-4721-b1c5-90f7f2bfdbac)

Hover over and click the branch you created, in our example above this was `branch-1` but click the branch with the name you chose. After doing so, this will redirect you to the home page of your GitHub repository.

![Screenshot (269)](https://github.com/user-attachments/assets/e53f4570-a7e9-4c6d-9638-f3bdb1bfc3be)

Once you're at the home page of your GitHub repository, the key difference to take note of is dropdown button for "Switching branches/tags". You'll notice your newly created branch is selected instead of `main`. You now have a carbon copy of the `main` branch where you can make your own isolated changes.
![Screenshot (271)](https://github.com/user-attachments/assets/afc1d51c-6c0e-4516-8934-cbb89603f685)

Open the script.md file. Before we making any changes, take note of the URL at the top of your browser. 

The URL path should be similar to the following: https://github.com/<your-username>/git-workshop/blob/<your-new-branch-name>/script.md.

Notice how <your-new-branch-name is prepended before script.md. This indicates you're viewing the the version of script.md stored on <your-new-branch-name>.

Try changing <your-new-branch-name> to main and notice how the branch you're on changes. Open a new tab and set the URL in your browser to the following (be sure to change <your-username> to your GitHub username):
https://github.com/<your-username>/git-workshop/blob/main/script.md

### Update script.md
Before we continue, check that you're working in the branch we created in the previous exercise. The URL at the top of your browser should say:
https://github.com/<your-username>/git-workshop/tree/<your-branch-name>

Open the script.md file. Like we did in a previous file, click the pencil icon at the top right of the page to edit the file. 

You can either make your own custom changes to the file or copy/paste our sample code snippet below into script.md:
```
def print_name(name):
  print(f`Your name is ${name}`)
```

### Commit your changes to script.md and push your changes to your feature branch
Now, let's take what we practiced before in the previous exercises. After you've made your changes, click the "Commit changes" button at the top right of the page. 

Add a short but descriptive commit message in the modal that pops up, then ensure `Commit directly to the <your-branch-name> branch` is selected. Then click "Commit changes".

## 4. Create a pull request from your change branch to main
