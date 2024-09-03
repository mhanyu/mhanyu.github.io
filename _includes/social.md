{% for social in site.data.social %}
[![{{ social.name }}](https://api.iconify.design/{{ social.icon | replace: ":", "/"  }}.svg?height=24&color={{ social.color | replace: "#", "%23"}})]({{ social.url }}){% endfor %}
