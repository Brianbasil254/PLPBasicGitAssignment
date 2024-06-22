# PLPBasicGitAssignment
Task 1: Repository Setup

1. GitHub Repository Creation:

  - Logged into my GitHub account.
  - Created a new repository on GitHub (called it "PLPBasicGitAssignment").
  - Initialized it with a README file.

Task 2: Local Setup

2. Local Folder Setup:

  - Created a new folder on my local machine (e.g., "PLPBasicGitAssignment").
  - Openned a gitbash terminal and navigated to the created folder.

3. Git Initialization:

  - Initialized the new Git repository in my local folder. { git init}

4. Connecting to GitHub:

  - Linked my local repository to the GitHub repository I created in Task 1. {git remote add origin <repository-url>}

   Replaced`<repository-url>` with the actual URL of my GitHub repository.
   
Task 3: Making Changes

5. Creating a File:

  - Inside my local folder, created a new text file ( `hello.txt`).

  - Added a simple text message ( "Hello, Git!").

6. Committing Changes:

  - Stage the changes.

  { git add hello.txt }

  - Committed the changes.

  { git commit -m "Add hello.txt with a greeting" }

Task 4: Pushing to GitHub

7. Pushing to GitHub:

  - Push the committed changes to your GitHub repository.

  { git push -u origin main }
