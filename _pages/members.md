---
title: Members
permalink: /members/
---

SweBIdx members work on the computational side of bioimaging across Sweden. Want to be listed? [Join us](/#join-us).

{% assign members = site.members | sort_natural: "last_name" %}
<ul class="member-list">
  {%- for member in members %}
    <li class="member-list__item">
      {% include swebidx/member-avatar.html member=member %}
      <div>
        <a class="member-list__name" href="{{ member.url | relative_url }}">{{ member.first_name }} {{ member.last_name }}</a>
        <div class="member-list__meta">
          {% include swebidx/member-affiliations.html affiliations=member.affiliations format="short" %}
        </div>
      </div>
    </li>
  {%- endfor %}
</ul>
