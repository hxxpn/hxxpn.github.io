
---
layout: home
title: "Home"
---
<div class="posts">
    {% for post in site.posts %}
        <article>
            <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
            Published on {{ post.date | date_to_string }}
            {{ post.excerpt }}
        </article>
    {% endfor %}
</div>﻿
