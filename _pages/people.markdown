---
title: People
layout: collection
permalink: /people/
collection: people
entries_layout: grid
classes: wide
---

<h3><a href="#current"></a>Current Members</h3>
<table style="border:0px;">
<colgroup>
       <col span="1" style="width: 40%;">
       <col span="1" style="width: 60%;">
    </colgroup>
{% for member in site.data.members %}
  <tr style="border:0px;"> <td style="border:0px;"> <a href="{{ member.url }}"><img style="display:block; width:100px;height: 100px; margin: 0 auto; border-radius: 50%; object-fit: cover" src="{{ member.image | prepend: "/assets/images/members/" }}"></a></td><td style="border:0px;">
          <a href="{{ member.url }}">{{ member.name }}</a>, {{member.role}}</td>
  </tr>
{% endfor %}
</table>