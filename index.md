---
layout: default.liquid
---
<img src='me.jpg' />
<h2>Reno DuBois</h2>

Hi, I'm Reno. I'm a software engineer living in St. Louis, Missouri, working at
<a href='https://www.lessannoyingcrm.com'>Less Annoying CRM</a>.
<br /><br />
I also code in my free time, you can view my <a href='https://github.com/renodubois'>GitHub</a>
or <a href='https://git.sr.ht/~reno'>SourceHut</a> profiles to see projects I've published.
<br /><br />
If you need to reach me, <a href='mailto:me@renodubois.com'>email</a> is preferred.
You can also follow me on <a href='https://twitter.com/renoinmo'>Twitter</a> or <a href='https://toot.cafe/renodubois'>Mastodon</a>, if you'd like.
<br /><br />
<h2>Blog</h2>
<p>Also available in <a href='rss.xml'>RSS</a>.

<ul>
{% for post in collections.posts.pages %}
<li>
	<a href='{{ post.permalink }}'>{{ post.title }}</a>
</li>
{% endfor %}
</ul>

