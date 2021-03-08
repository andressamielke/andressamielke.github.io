---
layout: default
---

# Posts

<div class="tags are-medium">
  {% for cat in site.categories %}
  <a href="/categories/#{{ cat | first }}">
    <span class="tag is-dark mr-2">
      <i class="fas fa-tag"></i> {{ cat | first }}
    </span>
  </a>
  {% endfor %}
</div>

{% for post in site.posts %}
<div class="card mb-4">
  <a href="{{ post.url }}">
  <div class="card-content">
    <div class="media">
      <div class="media-content">
        <p class="title is-4">{{ post.title }}</p>
        <p class="subtitle is-6">{{ site.title }}</p>
      </div>
    </div>
    <div class="content">
      {{ post.excerpt }}
      <br>
      <time datetime="2016-1-1">{{ post.date }}</time>
    </div>
  </div>
  </a>
</div>
{% endfor %}