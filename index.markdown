---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
header:
    overlay_filter: rgba(237, 27, 47, 0.3)
    overlay_image: /assets/images/head.jpg
---

<link rel="stylesheet" href="./assets/style.css">

We are **HyperMatrix Lab** from **[Dalhousie University](https://dal.ca)**. <br> <br>
We are passionate about **Natural Language Processing**, **Deep Learning**, and designing and coding **Trustworthy AI**.


## News 

<ul>
    {% for post in site.posts %}
        <li class="home_news_item">
        <a href="{{ post.url }}" class="home_news_title">{{ post.title }}</a>
        {{ post.excerpt }}
        </li>
    {% endfor %}
</ul>
