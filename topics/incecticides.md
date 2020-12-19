

{% for item in site.data.incecticides %}
The country of {{ item.name }} was created in {{ item.date }}. Its flag is {{ item.flag }}.
{% endfor %}
