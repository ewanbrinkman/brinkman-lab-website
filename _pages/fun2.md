---
title: Fun
subtitle:
description: Description.
featured_image: /images/scenery/brinkman-pumpkin.png
---

# Fun

*Lab pic outtakes and other stuff!*

<div class="gallery" data-columns="1">
  {% for fun_image in site.data.fun_with_info %}
    <img src="/images/fun/{{ fun_image.filename }}" alt="{{ fun_image.text }}" class="fun--image">
  {% endfor %}
</div>
