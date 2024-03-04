---
layout: archive
title: "Preprints"
permalink: /preprints/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my preprints on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}
