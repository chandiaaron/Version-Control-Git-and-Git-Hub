# GitHub Collaboration 

## How to add collaboration to your repo 

Assuming you have a repo set up we can invite people like so : 

- On the page of your repo click settings 

![Git collab Image](/images/git.JPG)

- Next we want to click on the collaborators tab on the side : 

![Git collab Image 2](/images/git2.JPG)

- Click **Add People** 
- we either use the git ID of the person we want to add or we can use their email 

![Git collab Image 3](/images/git3.JPG)
![Git collab Image 4](/images/git4.JPG)

- The people we are inviting should get an email to accept or decline the invitation 
- we can confirm our collaborators by refreshing the collaborators page to manage access 

![Git collab Image5](/images/git5.JPG)


- If we want to clone the repo locally we can click the code button and click the code button again we can either clone via https or ssh using the provided links 
- In order to clone we can use GitBash 

```GitBash
clone <URL LINK FOR HTTPS OR SSH>
```

![Git Image6](/images/git6.JPG)

## How to push changes 

- When working on the repo locally, once we have staged our files and pushed them we will be prompted to input a password. We want to generate a token. First go to settings on GitHub and scroll all the way down until you see developer settings, click that. 

- Now click generate new token 

- We want to provide a name and what we want to allow, in this case we want to allow pushes from the local to the remote repo. we can now generate. 

- We want to make sure we save our token as we wont have access to it after we leave this page, we will use this for our password.  

![Git Image7](/images/git7.JPG)
![Git Image8](/images/git8.JPG)
![Git Image9](/images/git9.JPG)
![Git Image10](/images/git10.JPG)
![Git Image11](/images/git11.JPG)

# Branches 

Using multiple branches instead of a single branch in a team setting is beneficial because:

- Isolation of Work
Each developer can work on their own feature or bug fix in a separate branch without affecting the main (e.g., main or develop) branch.

- Better Collaboration
Multiple developers can work on different branches simultaneously without conflicts. Once their work is ready, they can merge it into the main branch.

- Code Review & Quality Control
Using feature branches (e.g., feature/login-page) allows for pull requests (PRs), enabling teammates to review code before merging.

## Main, Dev, and Feature 

