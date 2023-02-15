# git basic commands

Clone a repository [(see also here)](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

```
git clone <repository_url>
```

Display current branch
```
git branch
```

Create a new branch (first ensure that you are in the main/master branch with the previous command)
```
git checkout -b <new_branch_name>
```

...
work in this new branch
...

Check the state of the working directory and the staging area
```
git status
```

Add a change of the working directory to the staging area
```
git add <filename>
```

Commit the added changes to the local repository
```
git commit -m "<commit_message>"
```

Upload local repository to the remote repository
```
git push
```

...or upload a new branch for the first time
```
git push --set-upstream origin <branch_name>
```

[Create a pull request to merge your branch into main/master](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

---
## Other useful commands

Get list of commits
```
git log
```

Change branch
```
git checkout <branch_name>
```

Fetch content from a remote repository and update the local repository
```
git pull
```

--- 

## Further reading
* [Git workflow fundamentals](https://dev.to/mollynem/git-github--workflow-fundamentals-5496)
* [Resolving merge conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line)


