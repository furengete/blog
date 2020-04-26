---
layout: post
title:  "Notes on Jekyll"
date:   2020-04-24 09:57:12 +0800
categories: Notes
permalink: /notes-jekyll/
---

Tutorial: [Jekyll - Static Site Generator]

---


## Creating a Site

- locally
{% highlight git %}
jekyll new <site>
bundle exec jekyll serve
{% endhighlight %}

---

## Hosting on Github Pages

### New repository

{% highlight git %}
git init
git checkout -b gh-pages
git status
git add .
git commit -m "intiial commit"
git remote add origin http://github.com/githubusername/newrepositoryname.git
git push origin gp-pages
{% endhighlight %}


### costum domain

1. Configuring **A records** with your DNS provider will point your custom domain to the following IP addresses

	- 185.199.108.153
	- 185.199.109.153
	- 185.199.110.153
	- 185.199.111.153

	Add in one **CNAME** record for your custom domain then github will create CNAME file in your github repo automatically.


2. Edit your `_config.yml` file in your project folder.

{% highlight git %}
cd your project folder
vi `_config.yml`
url: "http://yourcoustomdomain.com"
{% endhighlight %}


### update changes to site

{% highlight git %}
git add .
git commit -m "commit messages"
git push origin gh-pages
{% endhighlight %}



[Jekyll - Static Site Generator]: https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB