# GIT-CHEAT-SHEET

#### INSTALLATION & GUIS

With platform specific installers for Git, GitHub also provides the
ease of staying up-to-date with the latest releases of the command
line tool while providing a graphical user interface for day-to-day
interaction, review, and repository synchronization

#### GitHub for Windows

htps://windows.github.com

#### GitHub for Mac

htps://mac.github.com

For Linux and Solaris platforms, the latest release is available on
the official Git web site.

#### Git for All Platforms

htp://git-scm.com

#### SETUP

Configuring user information used across all local repositories

```
git config --global user.name “[firstname lastname]”
set a name that is identifiable for credit when review version history
```

```
git config --global user.email “[valid-email]”
set an email address that will be associated with each history marker
```

```
git config --global color.ui auto
set automatic command line coloring for Git for easy reviewing
```

#### SETUP & INIT

Configuring user information, initializing and cloning repositories

```
git init
```

initialize an existing directory as a Git repository

```
git clone [url]
```

retrieve an entire repository from a hosted location via URL

#### STAGE & SNAPSHOT

Working with snapshots and the Git staging area

```
git status

```

show modified files in working directory, staged for your next commit

```
git add [file]
```

add a file as it looks now to your next commit (stage)

```
git reset [file]
```

unstage a file while retaining the changes in working directory

```
git diff
```

diff of what is changed but not staged

```
git diff --staged
```

diff of what is staged but not yet commited

```
git commit -m “[descriptive message]”
```

commit your staged content as a new commit snapsho

## Authors

- [@AhmadPiracha]https://github.com/AhmadPiracha)
