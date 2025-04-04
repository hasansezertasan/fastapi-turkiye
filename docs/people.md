<!--
---
hide: [navigation]
---
-->

# Topluluk

## Kurucular

<!-- markdownlint-disable -->
{% if founders %}
<div class="user-list user-list-center">
{% for member in founders %}

<div class="user">
    <a href="{{ member.url }}" target="_blank">
        <div class="avatar-wrapper">
            <img src="{{ member.avatar }}"/>
        </div>
        <div class="title">@{{ member.login }}</div>
    </a>
    <div class="name">{{ member.name }}</div>
</div>

{% endfor %}
</div>
{% endif %}

{% if founders %}
{% for member in founders %}

[{{ member.name }}]

{% endfor %}
{% endif %}

<!-- Add refs from founders -->
{% if founders %}
{% for member in founders %}

[{{ member.name }}]: {{ member.url }} "{{ member.name }}"

[@{{ member.login }}]: {{ member.url }} "{{ member.name }}"

{% endfor %}
{% endif %}
<!-- markdownlint-enable -->
