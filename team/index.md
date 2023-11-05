---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

We are a highly engaged and collaborative team with people from multiple disciplines. The team consists of postdocs, students at all levels, and staff.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: programmer" %}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

Diverse teams do better research. We are committed to providing an inclusive environment and welcome candidates from diverse culture and educational backgrounds.

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% include section.html %}

## Alumni

These are past lab members who have moved on to Cambridge University, Boston University, Ludwig Maximilian University of Munich, other school programs, new jobs, or elsewhere.

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: alum" style="small" %}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/nsfc.jpg"
  link1="https://www.nsfc.gov.cn/"
  tooltip1="NSFC"

  image2="images/zju.png"
  link2="https://www.zju.edu.cn/main.htm"
  tooltip2="ZJU"

  image3="images/most.png"
  link3="https://www.most.gov.cn/index.html"
  tooltip3="MoST"

%}
