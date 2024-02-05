---
hide:
  - navigation
---
# İlerleyiş

## Emoji Haritası

| Emoji | Durum            | Açıklama                    |
| ----- | ---------------- | --------------------------- |
| 🤓     | İnceleme         | PR açıldı, Review ediliyor. |
| 🚧     | Yapım Aşamasında | Çalışma devam ediyor.       |
| 🔳     | Yapılacak        | Çevirmenini bekliyor.       |
| ✅     | Onaylandı        | Onaylandı.                  |

## İlerleyiş

{% if progress %}
<table>
    <thead>
        <tr>
            <th>Sayfa</th>
            <th>Bağlantı</th>
            <th>Durum</th>
            <th>Sebep</th>
            <th>Gönüllü</th>
            <th>Çeviren</th>
            <th>Gözden Geçiren</th>
        </tr>
    </thead>
    <tbody>
        {% for item in progress %}
        <tr>
            <td><code>{{item.page_name}}</code></td>
            <td>
            {% if item.pr_number %}
                <a href="https://github.com/tiangolo/fastapi/pull/{{item.pr_number}}">{{item.pr_number}}</a>
            {% endif %}
            </td>
            <td>:{{item.state}}:</td>
            <td>
            {% if item.reason == "new" %}
                Yeni sayfa
            {% elif item.reason == "outdated" %}
                Zaman Aşımı
            {% endif %}
            </td>
            <td>
                <a href="https://github.com/{{item.volunteer}}">@{{item.volunteer}}</a>
            </td>
            <td>
            {% if item.translator %}
                <a href="https://github.com/{{item.translator}}">@{{item.translator}}</a>
            {% endif %}
            </td>
            <td>
            {% if item.reviewers %}
                {% for reviewer in item.reviewers %}
                    <a href="https://github.com/{{reviewer}}">@{{reviewer}}</a>
                {% endfor %}
            {% endif %}
            </td>
        </tr>
        {% endfor %}
    </tbody>
</table>
{% endif %}

## Durum

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
            {% if page.state == "not-translated" %}
                Çevirilmedi
            {% elif page.state == "outdated" %}
                Zaman Aşımı
            {% elif page.state == "up-to-date" %}
                Güncel
            {% endif %}
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
