---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<ul>
{% for upgrade in site.data.cyberacme.upgrades %}
  <li>
    {{ upgrade.name }}
  </li>
{% endfor %}
</ul>
