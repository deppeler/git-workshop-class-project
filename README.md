# Fabulous Data Science Project

* deb
* beck
* jim

# INITIALIZE GIT REPO

```
git init
git status
```
# SET CREDENTIALS

Turn on the credential helper so that Git will save your password in memory for some time. By default, Git will cache your password for 15 minutes.

In Terminal, enter the following:

```
$ git config --global credential.helper cache
# Set git to use the credential memory cache
```

To change the default password cache timeout, enter the following:

```
$ git config --global credential.helper 'cache --timeout=3600'
# Set the cache to timeout after 1 hour (setting is in seconds)
```

# first steps

create or change files
```
git add to add files to tracked files
git commit to confirm changes
```

# UNSTAGE CHANGED FILES

```
git restore --staged README.md
```

# CREATE .gitignore file

```
vi .gitignore
results/
```

# Some configuration to make things better

```
git config --global user.name "Deb Deppeler"
git config --global user.email "deppeler@cs.wisc.edu"

git config --global --list
git config --list
```

# more commands

```
git log  -- show history
```

# csl to GitHub

```
git push origin master
```

# GitHub to csl

```
git pull origin master
```
