---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
### HERE ###

<div>{{ site.data.cyberacme.cyberacme.upgrades }}</div>

<div>
  <ul>
  {% for upgrade in site.data.cyberacme.cyberacme.upgrades %}
    <li>
      {{ upgrade.name }}
    </li>
  {% endfor %}
  </ul>
</div>
