---
layout: template
---

# Use of Incecticides

Based on the chemical nature, insecticides are classified into two groups:

{% for item in site.data.incecticides %}
- {{ item.name }}
-- {{ item.definition }}
{% endfor %}

## See also

-  [What is Organic Farming](intro.md)
-  [Benefits of Organic Farming](benefits.md)
-  [Methods in Organic Farming](methods.md)
