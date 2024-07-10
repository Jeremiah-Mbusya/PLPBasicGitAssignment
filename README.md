# PLPBasicGitAssignment

#Procedure

1. GitHub Repository Creation:

  - I Logged in to my GitHub account.

  - I created a new repository on GitHub named "PLPBasicGitAssignment"

  - Initialized it with a README file.



Task 2: Local Setup

2. Local Folder Setup:

  - I created a new folder on my local machine  named it "PLPBasicGitAssignment"

  - Opened git CMD and cd'd dir to created folder.
    cd c:/PLPBasicGitAssignment



3. Git Initialization:

  - Initialized a new Git repository in my local folder:
   git init



4. Connecting to GitHub:

  - Linked my local repository to the GitHub repository I created in Task 1.

   ```

git remote add origin https://github.com/Jeremiah-Mbusya/PLPBasicGitAssignment.git

   ```

  



Task 3: Making Changes

5. Create a File:

  - Inside the local folder, I created a new text file named `hello.txt`:
   '''
   touch hello.txt
'''
  - Added a simple text message 
  '''

  echo "Hello, Git!">hello.txt



6. Committing Changes:


   ```

   git add hello.txt

   ```

  - Commited the changes.

   ```

   git commit -m "Add hello.txt with a greeting"

   ```



Task 4: Pushing to GitHub

7. Pushing to GitHub:

  - Pushed the committed changes to my GitHub repository.

   ```

   git push -u origin master

   ```
