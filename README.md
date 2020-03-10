# CPSC_362_Sprint_1

## Directions
1. Download PyCharm and GitHub Desktop.
2. If Python 3.8 is not installed, make sure to install it. You can verify using the command, python --version.
3. Within GitHub Desktop, login and find the file menu tab on the top left to select clone a repository. Find this project then clone it. 
4. In PyCharm, open the cloned project. When you select a file, on the bottom right corner, it should say Python 3.8([project name]). On the bottom left corner, selecting the terminal table should also display a (venv) before the C:\ path. If it does not, then follow the sub-steps below. 
- Within the file menu tab on the top left, select settings. 
- Inside the settings menu, find the the Project: [project name] tab, expand the menu to set up the Project Interpreter. 
- Press the gear symbol next to the drop down menu and select Add.
- Select the new environment option if no error appears. Make sure the base interpreter contains the python.exe file in the most recent Python folder. 
(If the OK option is disabled, go into the project location and delete the venv folder. Then, try creating a new environment again.)
- Press OK to confirm the environment and exit out of settings.
5. Open the terminal located on the bottom left-hand corner. Make sure that (venv) appears before the C:\ path. If not, set up your interpreter again (Step 4).
6. Run the pip install commands for flask and flask_sql alchemy.
a. pip install flask
b. pip install flask-sql-alchemy
7. Use the command python app.py to run the project. 

## Resources
For HTML and Python, doing all the interactive exercises should be enough to explain the basics. For Flask, I suggest watching the whole video. If there are any unfamiliar words, I would recommend researching them to understand them. 

- HTML
https://www.w3schools.com/html/

Python
https://www.w3schools.com/python/default.asp

Flask
https://www.youtube.com/watch?v=Z1RJmh_OqeA

## GitHub Information
Make sure to create a branch for your own work. GitHub Desktop helps out with all of the git commands by providing a graphical interface. The menus allow quick branch creation, branch switches, and pulls without worry about having to remember each of the commands. The program also shows what changes that have been made compared to the last commit. Committing is also easier since there are checkboxes indicating what to include or not. Resetting the branch is also easier since it is available as a right-click option. 

Below are directions for both GitHub Desktop and GitHub terminal commands
### GitHubDesktop
##### Create a branch
- In current branch menu tab, the dropdown menu should display the branch list. Select master (stashing changes if needed), and create a new branch under the same current branch menu tab by inputing the new branch name in the text input and pressing new branch. This should create a branch based off of master instead of another in progress branch.
##### Commit changes
- Select the files you want to commit on the left menu bar by pressing the checkboxes. Add a message under the summary text box then press the blue commit button. On the top right menu, press the push origin button if it has not been done already. 
##### Switching branches
- Under the current branch tab, go into the drop down menu and select a branch. It is best to stash changes instead of bringing them onto a another branch. Otherwise, the changes you made will follow you to the new branch.
##### Updating branches
- On the top right menu, pressing the fetch origin button will allow the program to update to the current branch. 
##### Creating a pull request
- Select the branch and commit or discard or any changes. Then, create a pull request and attach other people for review. 


### GitHub Commands for terminal
##### git branch [branch-name]
- Creates the branch name, this should be only run once. It should also be based off of master (git checkout master).  
##### git checkout [branch-name]
- Switches to the branch, make sure you are on the right branch when you make changes. If the terminal says to stash or commit the changes, just enter git stash to return to later using git stash pop, or discard the changes using 'git checkout .'.
##### git branch
- Displays the list of branches as well as your current branch. 
##### git add . 
- Adds all files that were changed from the last commit .
##### git commit -m "[message]"
- Add a message to the commit.
##### git push origin --set-upstream [branch-name]
- Connects to the GitHub server and pushes the commit.
##### git pull
- Updates the branch if the program has not done so already.
