---
id: 12
title: Portfolio
date: 2018-10-09T08:43:19+00:00
author: Elizabeth Mamacos
layout: default
guid: https://mamacosmedia.wordpress.com/?page_id=5
sharing_disabled:
  - "1"
switch_like_status:
  - 'a:1:{i:0;i:0;}'
---
<p style="text-align:center">
  <strong>Digital Content Creation and Marketing </strong>
</p>

I have experience in creating and marketing digital content including but not limited to news and articles, blog content, SEO content, professional profiles, social networking, emails, user responses, marketing materials and also website copy from FAQs to meta tags and more. 

Over the course of my career I have published thousands of articles, shared to millions of web users, across a variety of topics, including parenting, women’s interest and career advancement. 

<p style="text-align:center">
  <strong>Here is a selection of my recent articles&nbsp;and&nbsp;blog&nbsp;posts:&nbsp;</strong>
</p>
<ul>

{% for post in site.posts %}
  <article>
    <h2>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    {{ post.content }}
  </article>
{% endfor %}