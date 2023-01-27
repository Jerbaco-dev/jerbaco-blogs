---
title: Welcome to my blog
---

## Blogs

[K8S - Troubleshooting]({% post_url 2023-01-27-Kubernetes | prepend: site.baseurl %})


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url}}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
