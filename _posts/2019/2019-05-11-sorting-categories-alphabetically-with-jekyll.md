---
layout: post
title: How to sort categories alphabetically with Jekyll
categories: Jekyll
---

When I created my blog using Jekyll, I forked the [Tale](https://github.com/chesterhow/tale/) theme, but I have since customized it to fit my needs. Among other things, I added a categories page. Jekyll provides [support for displaying categories](https://jekyllrb.com/docs/posts/#categories-and-tags), but it doesn't sort them alphabetically. For instance, as of the date of this post, my categories are Books, Documentation, GitHub, Lessons, Life, and Writing. When I initially used the code that Jekyll provided, GitHub ended up at the bottom of my categories list because Jekyll sorted my posts (and the categories they belonged to) in ascending order.

While exploring GitHub Gist, I came across [Phlow's Jekyll loop gist](https://gist.github.com/Phlow/57eb457898e4ac4c4a20) that allows me to sort my categories alphabetically or by any other variable. This is why GitHub's community is amazing. Developers all over the world openly share their code for anyone to use and modify.

## How sort categories alphabetically with Jekyll

_Note: Everyone has their own way of displaying their categories in the Jekyll themes. This is the method I used based on the theme I forked._

1. In the `_pages`folder, create a file called `categories.html`.
2. Set the layout, title, and permalink in the front matter.
```
 ---
layout: post
title: Categories
permalink: /categories/
 ---
```
3. Paste [Phlow's gist](https://gist.github.com/Phlow/57eb457898e4ac4c4a20) in the body of `categories.html`.

Modifying this Jekyll theme is one of my favourite activities. It gives me the chance to learn more about this static site generator and then document what I've discovered.
