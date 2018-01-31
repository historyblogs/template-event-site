---
title: Homepage 9 Footer
location: homepage
head:
  title: 
  subtitle: 
style:
  id: contact
  class: dark
  media:
    img:
      url_path: 
      pattern: 
      parallax: 
      overlay: 
      blur: false
  tint_color: rgba(163,166,152,0.6)
cta:
  headline: 
  btnText: 
  btnType: 
  btnLink: 
  subtext: 
---

<div class="col-sm-5">
    <h4 class="text-left">Contact Us</h4>
    {% include widgets/contact-form.html email="contact@example.com"%}
</div>

<div class="col-sm-5">
{% include map.html %}
</div>

<div class="col-sm-2">
<h4 class="text-left">Connect</h4>
{% include social-links.html %}

<h4 class="text-left">Visit Us</h4>
{% include widgets/visit-us.html %}
</div>
