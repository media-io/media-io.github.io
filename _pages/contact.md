---
layout: default
title: Media-IO | Contact
style: centered
permalink: /contact
---

# Contact us

<div class="contact-form">
  <form action="{{site.contact_action}}" method="POST">
    <div class="item">
      <label>
        Email Address *
      </label>
      <input type="email" name="_replyto" placeholder="Your email address...">
    </div>
    <div class="item">
      <label>
        Name *
      </label>
      <input type="text" name="name" placeholder="Your name...">
    </div>
    <div class="item">
      <label>
        Message *
      </label>
      <textarea name="message" placeholder="Your message..."></textarea>
    </div>
    <div class="actions">
      <input type="submit" value="Send Message" class="button">
    </div>
  </form>
</div>

<br/>
<br/>
Want to follow us, subscribe below:
<div class="actions subscribe">
  <a href="{{site.newsletter_action}}" target="_blank">
    <span class="button">
      <i class="fa fa-external-link"></i>
      Subscribe to our newsletter
    </span>
  </a>
</div>
