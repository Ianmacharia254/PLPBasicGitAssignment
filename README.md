# PLPBasicGitAssignment
Git basics
To create a GitHub repository, connect it to a local folder, and make commits and pushes, follow these detailed steps and commands:

Step 1: Create a GitHub Repository
Create a new repository on GitHub:

Go to https://github.com and log in to your GitHub account.
Click on the "+" sign in the upper right corner and select "New repository".
Enter a name for your repository (e.g., MyProject), optionally add a description, choose whether it should be public or private, and initialize it with a README file (optional but recommended).
Click on "Create repository".
Copy the repository URL:

Once the repository is created, copy the URL provided (e.g., https://github.com/yourusername/MyProject.git). You will use this URL to connect your local repository to the remote GitHub repository.
Step 2: Connect Local Folder to GitHub Repository
Open your terminal or command prompt:

Navigate to your local project folder:

bash

cd /path/to/your/local/project/folder
Initialize Git in the folder (if not already initialized):

bash

git init
Add the GitHub repository as a remote:

bash

git remote add origin https://github.com/yourusername/MyProject.git
Replace https://github.com/yourusername/MyProject.git with the URL you copied from GitHub.

Step 3: Make Commits and Pushes
Add files to the staging area:

Suppose you have a new file index.html. Add it to Git's staging area.
bash

git add index.html
Commit the changes:

Commit the staged changes with a descriptive message.
bash

git commit -m "Initial commit: Added index.html"
Push commits to GitHub:

Push your committed changes to the remote repository (GitHub).
bash

git push -u origin master
This command pushes your changes to the master branch. If you are using a different branch, replace master with the branch name.

Summary of Commands Used:
Initialization and Remote Setup:

bash

git init
git remote add origin https://github.com/yourusername/MyProject.git
Adding and Committing Changes:

bash

git add <file(s)>
git commit -m "Commit message"
Pushing Changes to GitHub:

bash

git push -u origin master
Notes:
Ensure you have Git installed on your local machine and configured with your GitHub credentials.
Replace placeholders (yourusername, MyProject, index.html, etc.) with your actual GitHub username, repository name, file names, etc.
Handle any authentication (e.g., using SSH keys or HTTPS with credentials) as per GitHub's guidelines.
Regularly pull changes from the remote repository (git pull) to stay updated with changes made by others.
