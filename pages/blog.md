---
title: Blog
permalink: /blog/
---

# Coconut Blog

This is the landing page for the IB and productivity blog!

Please also check out [cobbiliu.medium.com](cobbiliu.medium.com) for a public version of the posts! Leave a like (they call it a clap there), comment, follow, and subscribe if you'd like!

<p>Subscribe with <a href="{{ site.baseurl }}/feed.xml">RSS</a> to keep up with the latest blogs.
For site changes, see the <a href="https://github.com/{{ site.github_user }}/{{ site.github_repo }}/blob/master/CHANGELOG.md">changelog</a> kept with the code base.</p>
<br>

{% for post in site.posts limit:10 %}
   <div class="post-preview">
   <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
   <span class="post-date"><i>{{ post.date | date: "%B %d, %Y" }}</i></span>
   {% if post.author %}
	   <span class="post-author">by <b>{{ post.author }}</b> </span><br>
   {% endif %}
   {% if post.badges %}{% for badge in post.badges %}<span class="badge badge-{{ badge.type }}">{{ badge.tag }}</span>{% endfor %}{% endif %}
   {{ post.content | split:'<!--more-->' | first }}
   {% if post.content contains '<!--more-->' %}
      <a href="{{ site.baseurl }}{{ post.url }}">read more</a>
   {% endif %}
   </div>
   <hr>
{% endfor %}

Want to see more? See the <a href="{{ site.baseurl }}/archive/">Blog Archive</a>.
