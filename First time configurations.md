# First time configurations 

When using Git for the first time in GitBash, establishing the username and email is important because:
- every commit in Git is associated with an author. Setting your name and email ensures that your contributions 
<br/> are properly recorded and attributed to you. 
- If you push commits to a remote repo like GitHub, your email is used to link commits to your account.
- Git includes information in each commits metadata, making it clear who made changes, great for tracking project history. 
## Commands to establish username and email 
#### _when you configure your details globally this will apply to all repos on your system_ 

```commandline
git config --gloabl user.name "Your name"
git config --global user.email "Your email" 
```
#### _To ensure the configuration was done properly we can run, you should see your details assigned._ 

```commandline
git config --list
```
## Maintaining best practices 

#### _when you ran the command list it's important to note that the default branch may = master. It's good practice to change this to the word main._

```commandline
git config --global init.defaultbranch main 
git config --system init.defaultbranch main 
git config --list
```
## Hierarchy of Git Configuration (Priority Order)

- Local (Highest Priority) – Specific to the repository, overrides everything else.
- Global – Applies to the user’s Git environment but can be overridden by local settings.
- System (Lowest Priority) – Affects all users on the system unless overridden by global or local settings.

