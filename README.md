# readlab02

# INTRODUCTION

## Prerequisites

Before beginning this tutorial, it is highly recommended that you have a solid understanding of the Terminal *(for Mac)* or Command Line *(for Windows and Linux)*.

## Version Control












# `Seeing Your Remotes`

By running the git remote command, you can view the short names, such as `“origin,”` of all specified remote handles.
By using git remote -v, you can view all the remote *URLs next to their corresponding short names*

![ex](see1.jpg)

#Fetching

Fetching entails pulling data that you don't have from a remote project. Here is the command format: 🌲

> git fetch [remote-name]

💢 **Note:** git fetch solely pulls new data to a local repository; it does not merge changes with or modify your local work. We will discuss merging in a later section. Later, we will also discuss git pull , which allows for fetching and automatic merging.

# Renaming/Removing Remotes

**Rename :left_speech_bubble:	

To rename a remote’s short name, `use the git remote rename command.`

Example:
![ex2](see2.jpg)

# Commit Mistakes 💥

`You can use the –amend command when you need to alter a commit message or forgot to add some files.`

`**$ git commit --amend**`

*In the example above, you can use this command to easily change your commit message, if no changes were made since the newest commit*

`$ git commit -m “my first commit”`

`$ git add example_file`

`$ git commit --amend`


