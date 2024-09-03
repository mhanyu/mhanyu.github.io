
{% assign files = site.static_files | where: "file", true %}
{% if files.size > 0 %}
---
### Files

{% for item in files %}
- [![](https://api.iconify.design/ri/file-fill.svg?height=16) {{ item.name }}]({{ item.path | absolute_url }})
{% endfor %}

{% endif %}
