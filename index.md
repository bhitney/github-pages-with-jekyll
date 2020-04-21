(index content here)

{% for plan in site.azure %}
  Plan: 
  <h2>
    <a href="{{ plan.url }}.md">
      {{ plan.name }} - {{ plan.scenario }}
    </a>
  </h2>
{% endfor %}

(end of index content)
