# Welcome to the Home Page 

{% for post in site.posts %}
1. [{{post.title }}]({{ post.url }})
{% endfor %}
