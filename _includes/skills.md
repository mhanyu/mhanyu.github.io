
### My Tech Stack
{% for skill in site.data.skills %}
![{{ skill.name }}](https://api.iconify.design/{{ skill.icon | replace: ":", "/"  }}.svg?height=24){% endfor %}
