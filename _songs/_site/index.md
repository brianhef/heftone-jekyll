
*Song index page

{% for song in site.words %}
  <h2>
    <a href="{{ word.url }}">
      {{ word.name }} - {{ staff_member.position }}
    </a>
  </h2>
  <p>{{ word.content | markdownify }}</p>
{% endfor %}
