---
title: Contributors
description: Awesome people who have contributed to the campaign
---

{% include milestone.html %}

Thanks to all who have contributed to this repository! :raised_hands:

Not awesome yet? Get your name listed by making a pull request!

{% for contributor in site.github.contributors %}
- [{{ contributor.login }}]({{ contributor.html_url }})
{%- endfor -%}