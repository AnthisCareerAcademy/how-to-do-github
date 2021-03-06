# how-to-do-github

What is a repository?

A repository in git is a set of directories, with a master and branches, where
software is stored, and can be easily modified for future development. It also
saves backups of previous versions you have developed.

# BASIC VOCABULARY TERMS

These were found on the help page for GitHub, which is located here.
https://help.github.com/articles/github-glossary/

GIT - an open-source software version tracker, developed by Linus Torvalds
to manage Linux kernel development
CLONE - a downloaded copy of an online repository
FORK - cloning a repository, and then modifying it
BRANCHES - forks within your own repository, used to manage and keep track of
where files are stored within your git directories
COLLABORATOR - someone who has access to read and edit files within a
repository
COMMIT - a change in a file that git keeps track of, saving information
including who changed it, and when
ISSUE - suggested improvements, tasks, and questions, that can be contributed
by anybody, and that are moderated by collaborators
MERGING - taking changes from a fork or a branch and applying them to another
RELEASE - a new version of your program/repository

# HOW TO OPEN A NEW REPO

1) Select the plus icon on the top right of the top panel of the page.
2) From the dropdown, hit "New repository"

# HOW TO ADD FILES

If you are uploading a file to your repository:
  1) Select "Upload files in the proper branch you want to upload the file to
  2) Use the file manager to locate, and then upload it.
  
If you want to create a new file within the GitHub browser client:
  1) Select "Create new file" in the proper branch you want to create a new file in.

# HOW TO COMMIT A CHANGE

Just select one of the options:
  - Commit change to the master branch
  - Commit change to a new branch that you define
  - Commit change to an already existing branch
  
# OPENING PULL REQUESTS

First of all, "pull" is the wrong word; it should be "merge," as it is in GitLab.
Essentially, a pull request is when you want feedback from others, or you want to
make sure you are following convention, so you clone or fork an existing
repository into your own. This allows you, or others, to test code and make sure
everything is working properly.
  
# HOW TO PUSH A NEW VERSION

1) Select the releases tab on the bar under the name of your repository on its
main page.
2) Select "Draft a new release."
3) Type a version number for it, then select the branch you will want to use
as a version release. For the most part, the master branch is fine, unless
you are releasing beta software (under version 1). Instances for beta software
varies, so there is no right or wrong answer here.
4) Create a title and description for the release.
5) Select any binaries that you may want to package with your release, if any,
and put them into the binaries box.
6) IF IT IS A BETA, MAKE SURE TO LET YOUR USERS KNOW.
7) Select "Publish release" if it is ready to go, or "Save draft" to release
it later.
