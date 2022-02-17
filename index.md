---
layout: page
---
{% for page in site.posts%}
  {% include article.html %}
{% endfor %}