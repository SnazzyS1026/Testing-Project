# How to use Github
Practice using github

CLONING 

Step 1: Sign online to Github, create a new repository

Step 1a: Creating new repository
Click on "+" sign on upper right corner
Choose "New repository"
Select the owner
Name the Repository, give description, add README file, Choose "Python" on .gitignore, and "None" on license
Choose "Create repository"

Step 2:  Click on the green "Code" box to copy code

Step 3: Open up terminal

Step 4: Navigate to directory where you want github file to be cloned

For example: 
(base) C:\Users\sandr> cd OneDrive\Desktop\Metis\DS_Engineering\Projects

Step 5: Clone the file using the copied link from github

For example: 
(base)C:\Users\sandr> cd OneDrive\Desktop\Metis\DS_Engineering\Projects> git clone github_file_link

MODIFYING FILE ON LOCAL NETWORK AND ADDING TO GIT

Step 1: Go to directory and open jupyter notebook or open file (will open in Typora)

For example:
(base)C:\Users\sandr> cd OneDrive\Desktop\Metis\DS_Engineering\Projects\file_name> jupyter notebook

Step 2: This will open the file in jupyter notebook for modification

Step 3: Modify the file as needed locally on jupyter notebook

Step 4: Check git status

For example:
(base)C:\Users\sandr> cd OneDrive\Desktop\Metis\DS_Engineering\Projects\file_name>git status

Step 5: Add file to staging environment

(base)C:\Users\sandr> cd OneDrive\Desktop\Metis\DS_Engineering\Projects\file_name>git add file_name  # such as README.md

Step 6: Commit changes to git and add message to commit

base)C:\Users\sandr> cd OneDrive\Desktop\Metis\DS_Engineering\Projects\file_name>git commit file_name -m "Notes about the commit"

Step 7: Push changes onto github

(base)C:\Users\sandr> cd OneDrive\Desktop\Metis\DS_Engineering\Projects\file_name>git push

Step 8: The changes should show up on your github
