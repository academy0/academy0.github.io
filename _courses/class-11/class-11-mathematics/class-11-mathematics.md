---
layout: course
date: 2020-08-04
categories: courses
permalink: /courses/:title:output_ext
---

{% for i in (0..site.data.class_11_maths.chapters.size) %}  
 {% assign chapter = site.data.class_11_maths.chapters[i] %}
<div><a href="/courses/{{site.data.class_11_maths.code}}/chapter-{{i| plus: 1}}/section-1" {% if chapter.title == page.chapter %}class="active"{% endif %}>{{chapter.title}}</a></div>
{% endfor %}
