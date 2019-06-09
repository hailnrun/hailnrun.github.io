---
layout: default
---

<ul>
  {% for post in site.posts reversed %}
    <li>
      <a href="{{ post.url }}" style="color:purple">{{ post.title }}</a>
      <p style="
      padding: 1%;
      margin-left:10%;
      margin-right:20%;
      color:gray;
      font-size: 13px;">{{ post.content | strip_html | truncatewords:30 }}</p>
    </li>
    <hr>
  {% endfor %}
</ul>
