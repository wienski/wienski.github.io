{% if site.paginate %}
  <span>Paginator has {%- paginator.posts.size -%} posts</span>
{% else %}
  <span>Site has {%- site.posts.size -%} posts</span>
{% endif %}
