---
layout: default
title: Home
---

# Welcome to my book showcase

Thank you for visiting my GitHub Pages site. This website is dedicated to showcasing my latest book:

## Book Title

Introduce your book here, including a brief summary and cover image. You can also include a link to purchase the book or learn more about it.

## About the Author

Here's a little bit about me, the author:

- Brief bio
- Professional experience
- Relevant skills and expertise

## Blog

In addition to my book, I also write about topics related to computer engineering and other interests. Check out my latest blog posts for more:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%b %d, %Y" }})
{% endfor %}

## Contact

If you have any questions or comments about my book or website, please don't hesitate to get in touch:

- Email
- Social media links
