# CS615C-24253048
Step 1: Clone the Repository
git clone <repository_url>
Navigate into the cloned repository:
cd repository

Step 2: Configure Git (If Not Already Done)
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

Step 3: Create a New Branch
git checkout -b feature-branch

Step 4: Make Changes to Files
Edit files in the repository using any text editor.

Step 5: Check the Status of Changed Files
git status

Step 6: Stage the Changes
To stage all modified files:
git add .
Or stage a specific file:
git add filename.txt

Step 7: Commit the Changes
git commit -m "Your commit message"

Step 8: Push the Changes to GitHub
If pushing a new branch for the first time:
git push -u origin feature-branch
For an existing branch:
git push origin feature-branch

Step 9: Create a Pull Request 
Go to your GitHub repository.
Click on Pull Requests.
Click New Pull Request.
Select your feature-branch and compare it with main.
Click Create Pull Request.
Add a title and description.
Click Submit Pull Request.

Step 10: Merge the Pull Request
After review, click Merge Pull Request on GitHub.
Delete the branch if no longer needed.

Step 11: Pull the Latest Changes
To update your local repository with the latest changes:
git pull origin main
If working on a branch:
git pull origin feature-branch

