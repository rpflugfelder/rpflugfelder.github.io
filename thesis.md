---
layout: default
---

{% if site.show_excerpts %}

{%- assign posts = paginator.posts | default: site.posts -%}
{% for post in posts %}
{% if post.categories contains 'thesis' %}
  <article>
    {% include meta.html post=post preview=true %}
    {{ post.excerpt }}
    <div class="more"><a href="{{ post.url | relative_url }}">read more</a></div>
  </article>
{% endif %}
{% endfor %}

{% if paginator.total_pages > 1 %}
  <footer>
    {% if paginator.previous_page %}<a href="{{ paginator.previous_page_path | relative_url }}">« newer posts</a>{% else %}<span></span>{% endif %}
    <span>page {{ paginator.page }} of {{ paginator.total_pages }}</span>
    {% if paginator.next_page %}<a href="{{ paginator.next_page_path | relative_url }}">older posts »</a>{% else %}<span></span>{% endif %}
  </footer>
{% endif %}


{% else %}

<article>
  <header><h1>{{ include.title | default: page.title }}</h1></header>
  <ul class="archive">
    {% for post in site.posts %}
    <li>
      <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y-%m-%d" }}</time>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
  </ul>
</article>

{% endif %} )

