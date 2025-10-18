# Blogs

<ul>
  {% for post in site.posts %}
  <li style="padding: 7pt 11pt; border: 1px solid green; border-radius: 3pt;">
    <div style="display: flex; justify-content: space-between;">
      <a href="{{ post.url }}">
        {{ post.title }}: {{ post.subtitle }}
      </a>
      {{ post.date | date: "%b %-d, %Y" }}
    </div>
  </li>
  {% endfor %}
</ul>
