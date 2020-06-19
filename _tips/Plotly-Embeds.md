---
layout: post
date: 2020-06-11
---

# Plotly Embeds

In order to save Plotly graphs as an embed to share on the web, we first of all need to create an account on [Plotly Chart Studio](https://chart-studio.plotly.com/Auth/login/?action=signup&next=%2Fsettings%2Fapi). Finally, we just need to go to our account settings and get our API Key.

At this point we can go to our Python code, load the libraries and enter our account username and api_key.

```
import chart_studio
import plotly.express as px
import chart_studio.plotly as py
chart_studio.tools.set_credentials_file(username='TODO', api_key='TODO')
```

Now, every time we create a plot in the script, we can just add the following line in order to save our plot to our online account (each plot needs to have a unique name, otherwise it gets overwritten).

```
py.plot(fig, filename = 'Your plot name', auto_open=True)
```

Going to **View Your Profile** on our online account, we can then find our saved plots and get their sharable links for embeddings.

## Contacts

If you want to keep updated with my latest articles and projects [follow me on Medium](https://medium.com/@pierpaoloippolito28?source=post_page---------------------------) and subscribe to my [mailing list](http://eepurl.com/gwO-Dr?source=post_page---------------------------). These are some of my contacts details:

* [Linkedin](https://uk.linkedin.com/in/pier-paolo-ippolito-202917146?source=post_page---------------------------)

* [Personal Blog](https://pierpaolo28.github.io/blog/?source=post_page---------------------------)

* [Personal Website](https://pierpaolo28.github.io/?source=post_page---------------------------)

* [Patreon](https://www.patreon.com/user?u=32155890)

* [Medium Profile](https://towardsdatascience.com/@pierpaoloippolito28?source=post_page---------------------------)

* [GitHub](https://github.com/pierpaolo28?source=post_page---------------------------)

* [Kaggle](https://www.kaggle.com/pierpaolo28?source=post_page---------------------------)
