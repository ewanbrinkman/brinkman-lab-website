---
title: People
subtitle:
description: "People at the {{ site.data.settings.basic_settings.site_title }}."
featured_image: /images/people/group-photo-cropped-2.jpg
---

# People

Check out some lab pic [outtakes](/fun/) and other pics of honorary members!

<div class="people">
  <table>
    {% for person in site.data.people.current %}
    <tr>
      <td>
        {% if person.image_path %}
          {% if person.image_offset %}
            <img src="{{ person.image_path }}" alt="{{ person.name }}'s Headshot"
            style="object-position: {{ person.image_offset }};">
          {% else %}
            <img src="{{ person.image_path }}" alt="{{ person.name }}'s Headshot">
          {% endif %}
        {% else %}
        <img src="{{ site.data.settings.people.blank_headshot_image_path }}" alt="{{ person.name }}'s Headshot">
        {% endif %}
      </td>
      <td>
        <p><strong><big>{{ person.name | markdownify}}</big></strong>
        <br>{{ person.position }}</p>
        <p id="about">{{ person.about }}</p>
      </td>
    </tr>
    {% endfor %}
  </table>
</div>

{% assign alumni_size = site.data.people.alumni | size %}
{% if alumni_size != 0 %}
## Lab Alumni

*(Not all listed!)*

{% for person in site.data.people.alumni %}
{{ person.name }}
{% endfor %}
{% endif %}
