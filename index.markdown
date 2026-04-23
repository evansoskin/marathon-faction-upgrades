---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
### CYBERACME
<ul>
{% for upgrade in site.data.cyberacme.CyberAcme.upgrades %}
  <li>
    {{ upgrade.name }}
    <ul>
      {% for option in upgrade %}
        <li>
          {{ option }}
        </li>
      {% endfor %}
    </ul>
  </li>
{% endfor %}
</ul>
