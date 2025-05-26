---
layout: default
title: Blog
description: Latest insights and updates from the AMP Report development team
permalink: /blog/
---

<div class="main-content container">
    <section class="section">
        <h2>📝 AMP Report Blog</h2>
        <p>Stay updated with the latest insights, development progress, and industry analysis from the AMP Report team.</p>

        {% if site.posts.size > 0 %}
            <div class="features-grid">
                {% for post in site.posts %}
                    <article class="feature">
                        <h5><a href="{{ post.url | relative_url }}" style="color: #667eea; text-decoration: none;">{{ post.title }}</a></h5>
                        <p style="font-size: 0.9rem; color: #666; margin-bottom: 0.5rem;">{{ post.date | date: "%B %d, %Y" }}</p>
                        <p>{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
                        <a href="{{ post.url | relative_url }}" style="color: #667eea; font-weight: bold;">Read more →</a>
                    </article>
                {% endfor %}
            </div>
        {% else %}
            <div class="feature" style="text-align: center; padding: 3rem;">
                <h5>Coming Soon!</h5>
                <p>We're preparing exciting content about database architecture, real estate technology, and platform development. Check back soon for our first posts!</p>
            </div>
        {% endif %}
    </section>
</div> 