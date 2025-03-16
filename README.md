{% if page.lang == "ru" %}
{% include ru.md %}
{% elsif page.lang == "en" %}
{% include en.md %}
{% else %}
{% include es.md %}
{% endif %}
{% include common/contacts.md %}