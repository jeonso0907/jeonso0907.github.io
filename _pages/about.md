---
layout: about
title: about
permalink: /
# subtitle: <a href='https://www.osu.edu/'>The Ohio State University</a>.

profile:
  align: right
  image: sooyoung_2025.jpg
  image_circular: true # crops the image to make it circular
  # more_info: >
  #   # <p>555 your office number</p>
  #   # <p>123 your address street</p>
  #   # <p>Your City, State 12345</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # social block added inline below intro

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a first-year Ph.D. student in Electrical and Computer Engineering at [Boston University](https://www.bu.edu/), advised by Prof. [Wei-Lun (Harry) Chao](https://sites.google.com/view/wei-lun-harry-chao).

My research interests lie in computer vision and machine learning, with a primary focus on applications in robotics.

Previously, I received my M.S. and B.S. degrees in Computer Science and Engineering from [The Ohio State University](https://cse.osu.edu/).
<br>

<div class="social inline-social">
  <div class="contact-icons">{% include social.liquid %}</div>
  {% if site.contact_note %}
  <div class="contact-note">{{ site.contact_note }}</div>
  {% endif %}
</div>
