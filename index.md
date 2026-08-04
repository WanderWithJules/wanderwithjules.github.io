---
layout: default
title: Wander With Jules
---

<div style="background-image: url('https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=1600&q=80'); background-size: cover; background-position: center; height: 500px; display: flex; align-items: center; justify-content: center; color: white; text-align: center; margin-bottom: 50px;">

  <div>
    <h1 style="font-size: 58px; margin-bottom: 10px; text-shadow: 2px 2px 8px rgba(0,0,0,0.8);">
      Wander With Jules
    </h1>

    <p style="font-size: 22px; text-shadow: 2px 2px 6px rgba(0,0,0,0.8);">
      Honest reviews, spontaneous adventures and places worth experiencing.
    </p>
  </div>

</div>

<div style="max-width: 850px; margin: 0 auto; padding: 20px; text-align: center;">

  <h2>Every Place Has a Story</h2>

  <p>
  For me, it’s never just about the destination. It’s about the experience.
  </p>

  <p>
  From museums, attractions and scenic drives to restaurants, hidden gems and spontaneous day trips, I’ll share honest reviews, practical tips and the moments that made each visit memorable.
  </p>

  <p>
  Consider this your invitation to explore, discover and occasionally decide on a Friday night to go somewhere completely unexpected.
  </p>

</div>

<hr style="margin: 60px 0;">

<h2>Latest Stories</h2>

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.excerpt }}

[Read more]({{ post.url | relative_url }})

---
{% endfor %}
