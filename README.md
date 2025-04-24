# 👥 Team Collaboration Guide – GitHub (GUI + CLI)

Welcome to our project! This guide will walk you through how to contribute to this repository step-by-step using either **GitHub Desktop (GUI)** or the **Git CLI (Command Line)**.

> 💻 **Download GitHub Desktop**: [https://desktop.github.com](https://desktop.github.com)

---

## 📦 1. Clone the Repository

**GitHub Desktop (GUI):**
1. Open GitHub Desktop  
2. Go to **File → Clone Repository**  
3. Select the repository from the list or paste the URL  
4. Choose a local path  
5. Click **Clone**

**Git CLI:**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

##🌿 2. Create a New Branch
GitHub Desktop (GUI):

In the top bar, click the current branch name (e.g., main)

Click New Branch

Name your branch (e.g., feature/add-form)

Click Create Branch

Git CLI:
git checkout -b feature/add-form

##🛠 3. Make Changes to the Code
Once you have your project open:

GitHub Desktop (GUI):
Open your code editor (e.g., VS Code or Sublime Text)

Navigate to your project folder (the folder where you cloned the repo)

Open and edit the necessary files to implement your feature or bug fix

Save the changes in your editor

GitHub Desktop (GUI) Workflow:
GitHub Desktop automatically detects changes in the project.

If you've modified or added new files, you'll see them in the Changes tab on GitHub Desktop.

From this tab, you can review which files have been modified before committing.

##✅ 4. Stage and Commit Changes
GitHub Desktop (GUI):

After editing, go to the Changes tab in GitHub Desktop.

You'll see the list of modified files. Select the files you want to commit by checking the boxes next to them (or just commit all).

In the Summary box, add a commit message (e.g., "Add form validation").

Click Commit to [branch-name] to commit your changes.

Git CLI:
git add .
git commit -m "Your clear commit message"

##🚀 5. Push Your Changes
GitHub Desktop (GUI):
Once the commit is made, click Push origin in the top bar to upload your local branch and changes to GitHub.

Git CLI:
git push origin your-branch-name (But it will be always main origin)

##📩 6. Create a Pull Request (PR)
GitHub Desktop (GUI):

After pushing, GitHub Desktop will show a notification asking you to Create Pull Request

Click the Create Pull Request button, which will open your browser.

On GitHub, provide a title and description for the pull request (PR).

Click Create Pull Request to submit it for review.

Git CLI:

Go to your repo on GitHub

Click Compare & pull request

Add title + description

Click Create pull request

##🔍 7. Review and Merge the PR
A team member will review your pull request

Once approved, they’ll merge it into the main branch

After merging, delete your branch (GitHub will suggest this)

##🔄 8. Keep Your Main Branch Updated
GitHub Desktop (GUI):

Switch to the main branch from the top-left dropdown (click main)

Click Fetch origin to get the latest changes from GitHub

Then click Pull origin to update your local main branch

Git CLI:
git checkout main
git pull origin main

Then create a fresh branch for your next task:
git checkout -b new-feature-name

##💬 Collaboration Tips
Keep your commits clean and descriptive

Pull the latest changes before starting new work

Review PRs from others and leave feedback

Use GitHub Issues or Projects for task tracking


---

### What's New?
- Step-by-step guidance for editing code using GitHub Desktop: I added more detailed instructions on how to work with the code editor and how GitHub Desktop automatically detects your changes.
- Updated commit instructions: Added clarification on staging files for commit through the Changes tab in GitHub Desktop.
