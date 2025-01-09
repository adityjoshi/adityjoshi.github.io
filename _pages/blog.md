---
layout: default
permalink: /Blogs/
title: Blogs
nav: true
nav_order: 2
blogs:
  - title: "EP2: Relational Databases"
    link: "https://open.substack.com/pub/bashcraft/p/ep2-relational-databases?r=3u2izw&utm_campaign=post&utm_medium=web&showWelcomeOnShare=false"
    date: "December 28, 2024"
  - title: "A Good Project for You"
    link: "https://open.substack.com/pub/bashcraft/p/a-good-project-for-you?r=3u2izw&utm_campaign=post&utm_medium=web&showWelcomeOnShare=false"
    date: "December 21, 2024"
  - title: "The Coldplay Fiasco: Nobody Said It"
    link: "https://open.substack.com/pub/bashcraft/p/the-coldplay-fiasco-nobody-said-it?r=3u2izw&utm_campaign=post&utm_medium=web&showWelcomeOnShare=false"
    date: "December 11, 2024"
  - title: "There is Nothing Like a Roadmap"
    link: "https://bashcraft.substack.com/p/there-is-nothing-like-a-roadmap-or"
    date: "December 3, 2024"
---

<div style="text-align: center; font-family: 'Arial';">
  <h1 style="font-size: 3rem; color: red; margin-bottom: 10px;">Blogs</h1>
  <p style="font-size: 1.2rem;">
    I delve into research papers and resources that help me grow as a better engineer, documenting the insights and perspectives I gain along the way. Here’s a collection of all the blogs I’ve written so far.
  </p>
</div>

<hr style="border: 0; border-top: 2px solid #ccc; margin: 20px 20px;">
<div style="font-family: 'Arial'; color: #333;">
  {% for blog in page.blogs %}
    <div style="margin-bottom: 20px; border: 1px solid #ccc; padding: 15px; border-radius: 5px;">
      <h2 style="color: lightblue;">{{ blog.title }} - <span style="color: red;">Substack</span></h2>
      <p style="font-size: 0.9rem; color: grey;">Published on: {{ blog.date }}</p>
      <p><a href="{{ blog.link }}" style="color: blue; text-decoration: none;">Read more</a></p>
    </div>
  {% endfor %}
</div>
