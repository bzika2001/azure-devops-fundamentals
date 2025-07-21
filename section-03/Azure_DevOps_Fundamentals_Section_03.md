# 📘 Azure DevOps Fundamentals – Section 03: Azure Repos and Connecting to GitHub

## 📚 Table of Contents
- [📂 What is Azure Repos?](#-what-is-azure-repos)
- [🌲 Git Basics in Azure Repos](#-git-basics-in-azure-repos)
- [🔀 Branching and Merging Concepts](#-branching-and-merging-concepts)
- [✅ Pull Requests and Code Reviews](#-pull-requests-and-code-reviews)
- [🔗 Connecting Azure DevOps to GitHub](#-connecting-azure-devops-to-github)
- [🧭 Coming Up Next](#-coming-up-next)
- [🧠 Expert Insight](#-expert-insight)

---

## 📂 What is Azure Repos?

Azure Repos provides **Git repositories** or **Team Foundation Version Control (TFVC)** for source control.

- **Git repos** are distributed and widely used.
- **TFVC** is centralized, less common now.

Azure Repos helps teams collaborate on code, track changes, and manage versions effectively.

---

## 🌲 Git Basics in Azure Repos

Git stores snapshots of your project files. Common terms:

- **Commit**: Save changes to your local repo.
- **Push**: Send your commits to the remote repo.
- **Pull**: Get the latest changes from the remote repo.
- **Clone**: Copy a remote repo to your machine.

### Example: Basic Git Workflow

```bash
# Clone repo
git clone https://dev.azure.com/yourorg/yourproject/_git/yourrepo

# Make changes, then commit
git add .
git commit -m "Add new feature"

# Push changes
git push origin main

🔀 Branching and Merging Concepts
Branch: A separate line of development to isolate work.

Merge: Combine changes from one branch into another.

Common Branching Strategy
main: Stable production code

feature/*: New features or bug fixes

release/*: Preparing for release

Example: Create and switch to a feature branch

git checkout -b feature/add-login

```
✅ Pull Requests and Code Reviews
Pull Requests (PRs) let team members review and discuss code before merging.

Steps:

Developer pushes feature branch.

Opens a PR to merge into main or develop branch.

Reviewers comment and approve changes.

Merge the PR.

PRs help maintain code quality and knowledge sharing.

🔗 Connecting Azure DevOps to GitHub
You can link Azure DevOps pipelines to your GitHub repos:

In Azure DevOps, go to Pipelines > Create Pipeline.

Choose GitHub as your source.

Authenticate and select your GitHub repo.

Configure your pipeline YAML or classic editor.

Save and run the pipeline.

This enables CI/CD using GitHub as your code source but leveraging Azure DevOps tools.

🧭 Coming Up Next
Creating and managing pipelines

Automated testing and builds

Deploying to Azure

🧠 Expert Insight
Using Azure Repos with GitHub integration lets you combine the best of both worlds: GitHub’s social coding and Azure DevOps’ powerful CI/CD and project tracking.

<div style="display: flex; justify-content: space-between; margin-top: 20px;"> <a href="Section_02_Azure_Boards.md" style="background-color: #6c757d; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px;">⬅️ Previous Section</a> <a href="Section_04_Pipelines.md" style="background-color: #0078d4; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px;">Next Section ➡️</a> </div>
