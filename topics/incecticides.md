---
layout: template
---

# Using Incecticides


Based on the chemical nature, insecticides are classified into two groups:

{% for item in site.data.incecticides %}
- {{ item.name }}
{% endfor %}
