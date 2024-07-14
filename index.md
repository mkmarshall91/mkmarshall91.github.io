# Welcome to My Jekyll Site

This is the main page of my Jekyll site. You can customize this page by editing the `index.md` file.

## About

Write a brief introduction about your site here.

## Latest Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Contact

Include your contact information here.

{% include footer.html %}
```

Note: This file is intentionally left blank. You can customize the contents of this file to fit your needs.