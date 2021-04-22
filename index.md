---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <br />{{ post.excerpt | strip_html |strip_newlines | truncate: 240 }}
    </li>
  {% endfor %}
</ul>
