# My Projects

project1

My posts:

{% for post in site.posts %}  
  <li><a href="{{ BASE_PATH }}{{ post.url }}">{{post.date}} {{ post.title }}</a></li>
{% endfor %} 
