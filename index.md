{% if site.paginate %}
  {% assign posts = paginator.posts %}
  <span>Paginator has {%- posts.size -%} posts</span>
{% else %}
  {% assign posts = site.posts %}
  <span>Site has {%- posts.size -%} posts</span>
{% endif %}
