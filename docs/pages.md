---
hide: [navigation, toc]
---

# Sayfalar

{% if pages_manuel %}
<table>
    <thead>
        <tr>
            <th>Sayfa</th>
            <th>Durum</th>
        </tr>
    </thead>
    <tbody>
        {% for page in pages_manuel %}
        <tr>
            <td><a href="https://github.com/tiangolo/fastapi/blob/master/docs/en/docs{{page.name}}">{{page.name}}</a></td>
            <td>
                <a href="https://github.com/tiangolo/fastapi/blob/master/docs/tr/docs{{page.name}}">
                {% if page.state == "not-translated" %}
                    Çevirilmedi
                {% elif page.state == "outdated" %}
                    Zaman Aşımı
                {% elif page.state == "up-to-date" %}
                    Güncel
                {% endif %}
                </a>
            </td>
        </tr>
        {% endfor %}
    </tbody>
</table>
{% endif %}

<!-- Add refs from founders -->
{% if founders %}
{% for member in founders %}

[{{ member.name }}]: {{ member.url }} "{{ member.name }}"

[@{{ member.login }}]: {{ member.url }} "{{ member.name }}"

{% endfor %}
{% endif %}
