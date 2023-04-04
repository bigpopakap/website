# Welcome to my blog!

<ol>
  {% for post in site.posts %}
    <li>
      <article>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <p>{{ post.excerpt }}</p>
      </article>
    </li>
  {% endfor %}
</ol>
