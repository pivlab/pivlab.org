---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html dark=true %}

<span class=".center" style="font-size: var(--xxl);">
**We are hiring!**
</span>

<span class=".center" style="font-size: var(--large);">
We're currently hiring for several positions.
**Join us** and become part of our team.
</span>

{%
  include button.html
  text="Join the lab"
  link="join"
  style="button"
%}
