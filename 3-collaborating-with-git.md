# Collaborating with Git

📌 Learning objectives:

- Learn to collaborate with Git
- Discover GitHub/GitLab
- Start working in team


## Git alone

![](images/git-alone.png)


## The missing piece

![](images/git-with-server.png)


## Git remotes

![](images/decentralized.png)


### Managing remotes

Remote repositories are versions of your project that are hosted on the Internet
or network somewhere.

<br>

``` bash
$ git remote -v
origin   git@github.com:TailorDev/slides-git-at-michelin.git (fetch)
origin   git@github.com:TailorDev/slides-git-at-michelin.git (push)
```

``` bash
$ git remote add <name> <repo>
```

``` bash
$ git remote rm <name>
```

``` bash
$ git remote set-url <name> <new repo>
```


## Git clone

`git clone <repo>` downloads a full copy of a repository into a new directory.
Different protocols are supported: file, HTTPS, SSH, etc.

It automatically setups a default `origin` remote for `repo` that you can use
for `push` and `pull`.


## Git pull

`git pull <remote> <branch>` copies changes from a remote repository to a local
repository.


### Pull = Fetch + Merge

`git pull` is a shortcut for `git fetch` + `git merge`.

`git fetch` retrieves the commits from a remote repository, but do not apply
them on your working directory. `git merge` applies them.


## Git push

`git push <remote> <branch>` copies changes from a local repository to a remote
repository.


## Introducing GitLab

GitLab is an Open Source (MIT licensed) web-based Git repository manager with
wiki and issue tracking features.

![](images/gitlab-logo.png)


<!-- .slide: class="hands-on" -->
## 🚀 Hands-on

TODO
