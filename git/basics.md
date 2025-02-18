### git basics
``` 

Git is a distributed version control system used to track changes in code and collaborate on software projects. Here’s a quick overview of the basics:

1. ## Repositories

A Git repository is a directory that tracks all the changes made to files within it. There are two types:

(a) Local Repository: Stored on your machine.

(b) Remote Repository: Stored on a server like GitHub, GitLab, or Bitbucket.

2. ## Basic command

1. git init: Initializes a new Git repository.

2. git clone [url]: Copies an existing repository from a remote server to your local machine.

3. git status: Shows the current status of your repository, including untracked files, changes to be committed, and files not staged for commit.

4. git add [file]: Stages a file (adds it to the "staging area") to be included in the next commit.

5. git commit -m "message": Commits your staged changes with a message describing what has been done.

6. git pull: Fetches and merges changes from the remote repository to your local branch.

7. git push: Sends your committed changes to the remote repository.

8. git branch: Lists branches or creates a new branch.

9. git checkout -b [branch-name]: Switches to a different branch.

10. git merge [branch-name]: Merges changes from another branch into the current branch.