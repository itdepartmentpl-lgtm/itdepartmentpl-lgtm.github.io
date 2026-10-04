--
layout: post
author: sguthals
---
Write your blog post here.

Finally, in your index.md file, add the following code below the My Blog section:
<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>