{% if site.paginate %}
  {% assign posts = paginator.posts %}
  Paginator has {%- posts.size -%} posts
{% else %}
  {% assign posts = site.posts %}
  Site has {%- posts.size -%} posts
{% endif %}
