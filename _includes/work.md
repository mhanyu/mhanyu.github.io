{% for work in site.data.work %}
{% if work.url.size > 0 %}

- {{ work.sentence }} [**{{ work.name }}**]({{ work.url }})
{% else %}
- {{ work.sentence }} **{{ work.name }}**
{% endif %}
{% endfor %}
