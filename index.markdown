---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<ul>
  {% for menu in site.t[page.lang] %}
    <li><a href="{{ menu[1].url }}">{{ menu[1].name }}</a></li>
  {% endfor %}
</ul>
