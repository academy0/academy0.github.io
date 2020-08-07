---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

{% for item in site.data.courses %}

<h2>{{item.title}}</h2>
<ul>
    {% for entry in item.subjects %}
    <li><a href="{{ entry.url }}">{{ entry.name }}</a></li>
    {% endfor %}
</ul>
{%- endfor -%}
