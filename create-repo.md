# Set up the repo on github:
 -- If you're working on a team, only one person needs to do the set up stuff.
## 1 - Add a new repo on github
You just need to name it and save it. Click the "Create Repository" button and stay on this page. Instructions for the remote connection (what you'll need to connect the github repo to your local repo) are here and you'll need those for step 8 below (example: git remote add origin git@github.com:Deanna2000/DevelopmentNotes.git)
## 2 - Set up the repo on your local machine (in the terminal window):
1. mkdir <projectname> -- This creates the directory where you'll store your project on your machine.
1. cd <projectname> -- This navigates into to the folder. ***(automation idea)***
1. git init -- Makes the folder you are in into a local repo. You should see a "master" branch available now.
1. touch index.html .gitignore main.js style.css README.md -- Create your basic project files on the local repo ***(automation idea)***
1. git add . -- Add the changes to your local repo.
1. git commit -m "Initial Commit" - This packages up your changes so you will be able to send them to github. THIS IS THE ONLY COMMIT YOU WILL MAKE ON THE MASTER BRANCH.
1. git remote add origin (grab this info from the repo you created on github [step 1 above](#set-up-the-repo-on-github)
1. git push -u origin master -- This takes the commit you just made and sends it to github. You should see your files available now on the github repo. Yeah!
# You did it! The project is now set up!
## Time to Engage the Team:
1. Share the github url for the project with your team
1. Have each team member [clone the repo](clone-a-repo.md)


