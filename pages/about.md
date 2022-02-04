---
layout: page
title: About
description: Code the world!
keywords: Bear boy
comments: true
menu: 关于
permalink: /about/
---


## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}



