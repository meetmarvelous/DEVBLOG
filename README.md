# DEVBLOG

DEVBLOG is a blog website template created using HTML5, CSS3, and JavaScript. Based on the thought of producing templates for folks to apply later in their projects in order to lessen the amount of time spent building user interface for their blog site

# Contributor Rules

Are we lacking any of your favorite features, which you believe you can add If yes, We welcome you to aid to this project and make it better. To start donating, follow the steps mentioned below:

1. Create Issues.

2. Fork this repository.

2. Clone your forked copy of the project: <br>
    git clone https://github.com/YourGithubUsername/DEVBLOG.git

3. Navigate to the project directory: <br>
    cd DEVBLOG

4. Create a new branch: <br>
     git checkout -b YourBranchName

5. Make changes in source code: <br>

6. Stage your changes and commit: <br>
    git add . <br>
    git commit -m "<your_commit_message>"

7. Push your local commits to the remote repo: <br>
    git push origin YourBranchName

8. Create a PR

9. If someone will contribute to this repository, then those modifications will not be reflected in your local # repository. For correcting that:

10. Setup a reference(remote) to the original repository to obtain all the changes from the remote: <br>
    git remote add upstream https://github.com/meetmarvelous/DEVBLOG.git

11. Check the remotes for this repository : <br>
    git remote -v 

12. Fetching from the remote repository will bring in its branches and their relevant commits: <br>
    git fetch upstream

13. Make sure that you're on your master branch: <br>
    git checkout main

14. Now that we have downloaded the upstream repository, we want to integrate its modifications into our local branch. This will bring that branch into sync with the source, without losing our local modifications : <br >
git merge upstream/main
