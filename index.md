---
layout: default
title: Home
---

# Hello World!

My name is Leon Meyer. I am a Software Engineer from Hamburg, Germany.  
This blog serves as a brain dump for my interests and topics I think about.

The tech stack I am most comfortable with consists of TypeScript-based frameworks, mostly Angular and Next.js, a .NET backend, and Azure cloud infrastructure.

In my free time, I am a guitarist in a pop punk band, so maybe I will write about this as well.

If you have any questions or just want to chat with me, feel free to contact me!

All posts will be written by me. AI will only be used to correct my posts since English is not my mother tongue.

Happy reading!

## Latest Posts

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    ({{ post.date | date: "%d.%m.%Y" }})
  </li>
{% endfor %}
</ul>
