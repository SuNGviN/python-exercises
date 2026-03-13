# python-exercises

Repository for storing scripts in python.

# Course name: Introduction to CS and Programming using Python

---

Git Instructions:

1. Install Git
Open your terminal and install Git using pacman:

sudo pacman -S git

2. Configure Git
Set up your global user name and email, which are required for committing changes: 

git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"

3. Basic Git Usage

    Clone a repository: Download an existing repository to your local machine:\
git clone <repository_url>

    Initialize a new repository: Start a new Git repository in the current directory:
git init

    Check status: See which files have been modified or staged:
git status

    Add changes: Stage changes for commit:
git add <file_name>  # Add a specific file
git add .            # Add all changes in the directory

    Commit changes: Save the staged changes with a message:
git commit -m "Your commit message"

    Push changes: Upload local commits to a remote repository:
git push

    Pull changes: Update your local repository with changes from the remote:
    bash

    git pull
