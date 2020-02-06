---
layout: default
title: Media-IO | News
---

# News & Events
<div class="actions subscribe" style="text-align: center;">
  <a href="{{site.newsletter_action}}" target="_blank">
    <span class="button">
      <i class="fa fa-external-link"></i>
      Subscribe to our newsletter
    </span>
  </a>
</div>

<ul class="posts">
  {% for post in site.posts %}
    <li class="post">
      <h2>
        {{ post.title }}
      </h2>
      <div class=date>
        {% if post.start_date %}
          {% assign currentdate = post.start_date %}
          {% include date.html %}
          &#8594;
          {% assign currentdate = post.end_date %}
          {% include date.html %}
        {% else %}
          {% assign currentdate = post.date %}
          {% include date.html %}
        {% endif %}
      </div>
      <div class="wrapper">
        {% if post.image %}
          <span class="post-image left">
            <img src="/assets/images/{{post.image}}" />
          </span>
        {% endif %}
        <div class="post-content">
          {{ post.excerpt }}
          {% if post.bandeau %}
            <span class="post-image bandeau">
              <img src="/assets/images/{{post.bandeau}}" />
            </span>
          {% endif %}
        </div>
      </div>
    </li>
  {% endfor %}
</ul>
