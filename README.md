# Github Merge Options

The goal of this repository is to provide examples of using the 3 Github options available for merging PRs:
- Merge
- Squash and Merge
- Rebase and Merge

More information here: [Merge methods on GitHub](https://docs.github.com/en/github/administering-a-repository/about-merge-methods-on-github)

## Branches

All branches will be merged into master using the option defined by their names:
- rebase-branch
- squash-branch
- merge-branch

## Rebase and Merge

All commits from your branch `rebase-branch` are added to `master`
In this example we have the following commits:
- rebase: adding README.md file
- rebase: add information to README.md
- rebase: fix typo
- rebase: add rebase branch merging info

![Rebase PR](images/01_rebase_pr.png)

![Master Result](images/02_rebase_result.png)

## Squash and Merge

All commits from your branch `squash-branch` turn into a single commit that is added to `master`
When merging the PR, Github allows you to update the commit message to explain the purpose of the PR
In this example we have the following commits:
- squash: add some images about rebase and merge option
- squash: update image to focus on Github option for rebase
- squash: add squash information and .gitignore

![Squash PR](images/03_squash_pr.png)

![Squash Commit Form](images/04_squash_commit_form.png)

![Squash Result](images/05_squash_result.png)

## Merge

This is the default method and generates a merge commit from your `merge-branch` branch into `master` 
In this example we have the following commits:
- merge: add borders to images
- merge: adds information about Github merge option


### Author

Douglas Nomizo
