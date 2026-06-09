---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: About
permalink: /
---

<p>
  I'm a developer and technical writer focused on documenting and building enterprise software systems. I create and use software tools to work with data and content.
</p>

<h2>
  Contact Me
</h2>

<ul class="social-media-list">
  {%- if site.github_username -%}<li><a href="https://github.com/{{ site.github_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#github' | relative_url }}"></use></svg> <span class="username">{{ 'GitHub Profile' | escape }}</span></a></li>{%- endif -%}
  {%- if site.linkedin_username -%}<li><a href="https://www.linkedin.com/in/{{ site.linkedin_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use></svg> <span class="username">{{ 'LinkedIn Profile' | escape }}</span></a></li>{%- endif -%}
  {%- if site.rss -%}<li><a href="{{ 'feed.xml' | relative_url }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#rss' | relative_url }}"></use></svg> <span>{{ site.rss | escape }}</span></a></li>{%- endif -%}
</ul>
