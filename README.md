# PLPBasicGitAssignment

This repository contains a simple text file (`hello.txt`) created for learning basic Git operations.

## Steps and Commands Used

### Task 1: GitHub Repository Creation

1. **Log in to GitHub:**
   - Accessed GitHub in a web browser and logged into my account.

2. **Create a New Repository:**
   - Clicked on the "+" sign and selected "New repository".
   - Entered "PLPBasicGitAssignment" as the repository name.
   - Added a description and checked "Initialize this repository with a README".
   - Clicked on "Create repository".

### Task 2: Local Setup

3. **Local Folder Setup:**
   - Created a new folder named `PLPBasicGitAssignment` on my local machine.

4. **Open Terminal or Command Prompt:**
   - Opened a terminal or command prompt application.

5. **Navigate to Created Folder:**
   - Navigated to the `PLPBasicGitAssignment` folder using the `cd` command:
     ```bash
     cd path/to/PLPBasicGitAssignment
     ```

6. **Initialize Git Repository:**
   - Initialized a new Git repository in the local folder:
     ```bash
     git init
     ```

### Task 3: Making Changes

7. **Create a File:**
   - Created a new text file named `hello.txt` with the following command:
     ```bash
     echo "Hello, Git!" > hello.txt
     ```

### Task 4: Committing and Pushing Changes

8. **Stage and Commit Changes:**
   - Staged the `hello.txt` file for commit:
     ```bash
     git add hello.txt
     ```
   - Committed the changes with the following commit message:
     ```bash
     git commit -m "Add hello.txt with a greeting"
     ```

9. **Connecting to GitHub:**
   - Linked the local repository to the GitHub repository using the following command:
     ```bash
     git remote add origin <repository-url>
     ```
     Replace `<repository-url>` with the actual URL of the GitHub repository.

10. **Pushing to GitHub:**
    - Pushed the committed changes from the local repository to GitHub:
      ```bash
      git push -u origin main
      ```
      Note: Adjusted `main` if the default branch name is different.

### Task 5: Verification

11. **Verify on GitHub:**
    - Accessed the GitHub repository in a web browser.
    - Confirmed that the `hello.txt` file and commit message were visible under the "Code" tab.

## Conclusion

By following these steps, I successfully set up a GitHub repository (`PLPBasicGitAssignment`), created and modified a `hello.txt` file locally, and pushed these changes to GitHub using Git commands.
