# Version Control, Git and GitHub Explained

**What is Version Control?**

  Version controls is a system that tracks changes to files over time. it allows multiple people to collaborte on a project, keeps track of revisions and revert back to earlier verions if needed.Version control is essential for managing projects expecially in sofware development where it helps in maintaining code itegrity and history.

## Git Vs GitHub: What is the difference?
  
+ **Git:** Git is a distributed version control system that allows developer to keep track of changes to code or files. it can be used on your local machine and provides functionalities like branching, merging and committing of changes.

+ **GitHub:** GitHub is a web-based platform that uses Git for version control. it provides a cloud-based interface to host and manage Git repositories, collaborate with other developers and access a range of tools for project management and code review.

## GitHub Alternatives

1. **GitLab:** GitLab is a web-based open-source platform that provides Git repository management, CI/CD piplines and integrated security features.
2. **Bitbucket:** Bitbucket is also a cloud-based Git repository management tool integrated with JIRA and other Atlassian products that are ideal for teams using the Atlassian suite.
3. **SourceForge:** A free web-based platform offering tools for project management, code hosting  and collaboration. it is popularly used for open-source projects.

## Git Fetch vs. Git Pull

+ **Git Fetch:** This Git command downloads new data from a remote repository but does not integrate it with your local working files. it updates the local copy of the repository's inforamtion like branches and commits wothout merging any changes. Below is an example of the Git Fetch command.

    ```bash
    git fetch
    ```

+ **Git Pull:** This Git command fetches the data from a remote repository and automatically merges it with your local working files. it is basically the combination of `git fetch` and `git merge`. Below is an example of the command.

    ```bash
    git pull
    ```

## Git Rebase Explained

**Git Rebase:** Rebase is a way of integrating changes from one branch into another instead of merging. When you merge to a repository, it creates a new commit for the merge but rbae moves all the commits from your current branch to the base of the branch you are rebasing onto. Below is the git command and example:

```bash
git rebase <branch>
```

For example if our branch name is main:

```bash
git rebase main
```

## Git Cherry-pick Explained

**Git Cherry-pick:** Cherry-pick allows you to apply specific commit from one branch onto another branch. This is useful when you need to bring in a particuler change without merging the entire branches. Below is the Git command and example:

```bash
git cherry-pick <commit>
```

For example if our commit id is 'foobar':

```bash
git cherry-pick foobar
```
