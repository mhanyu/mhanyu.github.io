{% for button in site.data.links.buttons %}
### {{ button.category }}
  {% for item in button.items %}
- [![](https://api.iconify.design/{{ item.icon | replace: ":", "/"  }}.svg?height=16) {{ item.title }}]({{ item.url }})
  {% endfor %}
{% endfor %}
