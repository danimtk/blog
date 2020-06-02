---
layout: post
date: 2020-06-02
---

# Python Environments Management

In order to create a virtual environment in Python we need first of all to install the Python Virtualenv library.

```
pip install virtualenv
```

At this point we can create our environment using either `virtualenv .env` or `python -m venv .env` (where .env is our chosen local environment name).

Now we can anytime activate from Windows terminal the virtual environment using:

```
.env\Scripts\activate.bat
```

From now on we can then install all the libraries we need using `pip install {package name}`.

Once finished, we can then create a requirements.txt file containing all the libraries installed in our environment using:

```
pip freeze > requirements.txt
```

In this way, different collaborators/users can easily reproduce your same working environment by using the following command from their machine.

```
pip install -r requirements.txt
```

Once finished working with our environment, we can then simply deactivate it by typing `deactivate` in our command window.

## Contacts

If you want to keep updated with my latest articles and projects [follow me on Medium](https://medium.com/@pierpaoloippolito28?source=post_page---------------------------) and subscribe to my [mailing list](http://eepurl.com/gwO-Dr?source=post_page---------------------------). These are some of my contacts details:

* [Linkedin](https://uk.linkedin.com/in/pier-paolo-ippolito-202917146?source=post_page---------------------------)

* [Personal Blog](https://pierpaolo28.github.io/blog/?source=post_page---------------------------)

* [Personal Website](https://pierpaolo28.github.io/?source=post_page---------------------------)

* [Patreon](https://www.patreon.com/user?u=32155890)

* [Medium Profile](https://towardsdatascience.com/@pierpaoloippolito28?source=post_page---------------------------)

* [GitHub](https://github.com/pierpaolo28?source=post_page---------------------------)

* [Kaggle](https://www.kaggle.com/pierpaolo28?source=post_page---------------------------)
