---
title: Fun
subtitle:
description:
featured_image: /images/scenery/brinkman-pumpkin.png
---

# Fun

*Lab pic outtakes and other stuff!*

<ul class="fun--list">
  {% for fun_image in site.data.fun_with_info %}
  <li>
    {{ fun_image.text }}
    <img src="/images/fun/{{ fun_image.filename }}" alt="{{ fun_image.text }}"> 
  </li>
  {% endfor %}
</ul>
