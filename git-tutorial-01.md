---
layout: page
title: 
subtitle: 
---


## Contributing to DeepPush repositories
Developed by Kayode Olaleye, ...

This guide gives a quick start on contributing to [Toxicology](https://github.com/deep-push360/toxicology) - Our first Kaggle competition repository.

This guide assumes the reader has an account on GitHub and already familiar with the basics of git. Hence, details about 'forking', 'cloning', 'adding', 'commiting', 'pulling', and 'pushing' will not be covered now. This guide is basically a cheat-sheet to help team members easily get started with collaborating on different DeepPush's projects.

**Step 1**: Go to the repository on github: https://github.com/deep-push360/toxicology and click the “Fork” button at the top right to have your personal remote copy of the repository.

**Step 2**: To create a local copy of the 'forked' repository, open a terminal/shell and type



```
$ git clone https://github.com/username/toxicology.git 
```

Remember to change username to your GitHub username.

From the same terminal path, change into that project directory:


```
$ cd toxicology
```

**Step 3**: Connect to the original repository (in this case, https://github.com/deep-push360/toxicology.git 


```
$ git remote add deep-push360 https://github.com/deep-push360/toxicology.git 
```

To check the remote add setup:


```
$ git remote -v
```

**Step 4**: Make changes to any file in the local copy and `git add` and `git commit` those changes


```
$ git add filename
$ git commit -m 'updated filename'
```

**Step 5**: Check that your version is up to date relative to your **deep-push360**'s version. It is very important to always do this before you make changes to any file(s) locally. This will pull down and merge all of the changes that has been made to deep-push360 version.


```
$ git pull deep-push360 master
```

**Step 6**: Push them back to your remote copy


```
$ git push
```


## Submitting a Pull Request

After completing the above procedure, you are now ready to submit a pull request. Submitting a pull request is important in a collaborative work. This helps each team member to comment, critique and discuss the changes you have made to any files. Once all collaborators are happy, your changes can then be merged with **deep-push360**'s remote version.

This section will only cover how to create a pull from a forked repository. Creating a pull request from a branch within a repository will be covered when the need arises.

- To create a pull request, you must have changes committed to the your forked copy.
- Go to the [toxicology](https://github.com/deep-push360/toxicology) page on github. And click on "Pull Request" button in the repo header.
- Pick the branch you wish to have merged using the "Head branch" dropdown.
- Enter a title and description for your pull request.
- Finally, click on the green "Send pull request" button to finish creating the pull request.

