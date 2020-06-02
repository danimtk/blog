---
layout: post
date: 2016-06-02
---

# Basic Git Workflow

1) Get repository from remote:

```
git clone {link}
```

2) Create local branch:

```
git checkout -b {branch name}
```

3) Add branch to remote repository:

```
git push origin {branch name}
```

4) Add files to local branch:

```
git add .
```

5) Save locally the added files:

```
git commit -m {"commit description"}
```

6) Send updates to remote repository:

```
git push origin {branch name}
```

From there onward to keep adding updates from local branch to master:

```
git checkout -b {branch name}
git add .
git commit -m {"commit description"}
git push origin {branch name}
```

To add branch updates from local branch to master, do `git checkout master` and then `git merge {branch name}`.

To get updates from remote to your branch, use `git pull origin {branch name}`. If the local repository is not updated with all the branches created on remote need first to use `git fetch origin`.

## Contacts

If you want to keep updated with my latest articles and projects [follow me on Medium](https://medium.com/@pierpaoloippolito28?source=post_page---------------------------) and subscribe to my [mailing list](http://eepurl.com/gwO-Dr?source=post_page---------------------------). These are some of my contacts details:

* [Linkedin](https://uk.linkedin.com/in/pier-paolo-ippolito-202917146?source=post_page---------------------------)

* [Personal Blog](https://pierpaolo28.github.io/blog/?source=post_page---------------------------)

* [Personal Website](https://pierpaolo28.github.io/?source=post_page---------------------------)

* [Patreon](https://www.patreon.com/user?u=32155890)

* [Medium Profile](https://towardsdatascience.com/@pierpaoloippolito28?source=post_page---------------------------)

* [GitHub](https://github.com/pierpaolo28?source=post_page---------------------------)

* [Kaggle](https://www.kaggle.com/pierpaolo28?source=post_page---------------------------)
