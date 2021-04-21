<ul>
  {% for post in site.posts %}
    <li>
      <a href="_posts/{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
