<!--
---
hide: [navigation, toc]
---
-->

# İlerleyiş

FastAPI dokümantasyonunun Türkçe çeviri koordinasyon sayfasına hoş geldiniz.

Bu sayfada çeviri sürecindeki ilerleyişi görebilir ve diğer gönüllülerle koordinasyon sağlayabilirsiniz.

Çevirmek istediğiniz bir sayfa varsa ve bu sayfa aşağıdaki listede yoksa, [progress.yml][progress.yml] dosyasının en altına kayıt ekleyebilirsiniz.

Mesela ben `/release-notes.md` sayfasını çevirmek istiyorum ve bu sayfa aşağıdaki listede yok. O zaman [progress.yml] dosyasının en altına aşağıdaki gibi bir kayıt eklemem gerekir:

```yaml
- page_name: /release-notes.md
  pr_number:
  state:
  reason: new
  volunteer: hasansezertasan
  translator:
  reviewers:
```

Bu kayıtta:

* `page_name`: Çevirmek istediğiniz sayfanın adı.
* `reason`: Bu sayfanın çevrilmeye ihtiyacı olup olmadığını belirtir. `new` daha önce çevirisi yapılmamış yeni bir sayfa olduğunu, `outdated` ise çevirinin güncellenmesi gerektiğini belirtir.
* `volunteer`: Sayfayı çevirmek isteyen gönüllünün GitHub kullanıcı adı, bu durumda `hasansezertasan`.

Sonraki aşama bir "Pull Request" (PR) açmaktır. PR'ı açtıktan sonra PR numarasını `pr_number` alanına eklerseniz sayfayı ziyaret edenler kabul edilmemiş PR'ları daha kolay görüp inceleyebilirler. Ha! Unutmadan, çeviri dosyasını çevirdiğinizde `translator` alanına kendi GitHub kullanıcı adınızı eklemeyi unutmayın.

<!-- markdownlint-disable -->
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
            <td>
            {% if item.state == "review" %}
                İnceleniyor
            {% elif item.state == "done" %}
                Tamamlandı
            {% elif item.state == "closed" %}
                Kapatıldı
            {% else %}
                Geliştirme Aşamasında
            {% endif %}
            </td>
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

<!-- Add refs from founders -->
{% if founders %}
{% for member in founders %}

[{{ member.name }}]: {{ member.url }} "{{ member.name }}"

[@{{ member.login }}]: {{ member.url }} "{{ member.name }}"

{% endfor %}
{% endif %}
<!-- markdownlint-enable -->

[progress.yml]: https://github.com/hasansezertasan/fastapi-turkiye/blob/main/docs/data/progress.yml
