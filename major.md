---
layout: page
title: Major
permalink: /major/
---
<div class="majors">
  {% for major in site.majorss %}
    <article class="major">

      <h1><a href="{{ site.baseurl }}{{ major.url }}">{{ major.title }}</a></h1>

      <div class="entry">
        {{ major.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ major.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>