---
layout: page
title: Home
slug: home
---
Developer of open source framework for Machine Vision - [SimpleCV](http://simplecv.org/). My majority of work is in the field of Computer Vision and Image Processing. Apart from that, I like to develop applications and try to learn new things. I have started working with Android and Javascript apart from Python, C and C++.

I am an active freelancer so if you want to get in touch, <a href="mailto:jayrambhia777@gmail.com">say Hi!</a>.

<!--
Events
{% for post in site.posts limit:5 %}
{% if post.category == "Event"%}
- **[{{ post.title }}]({{ post.url }})**
{% endif %}
{% endfor %}
-->

### Articles
{% for post in site.posts limit:5 %}
{% if post.category == "Blog"%}
- **[{{ post.title }}]({{ post.url }})**<!-- -->
{% endif %}
{% endfor %}


### Projects
{% for post in site.posts limit:5 %}
{% if post.category == "Project"%}
- **[{{ post.title }}]({{ post.url }})**
{% endif %}
{% endfor %}
- **[Lenx](http://lenxapp.com/)**
- **[Waeo](http://getwaeo.com/)**
