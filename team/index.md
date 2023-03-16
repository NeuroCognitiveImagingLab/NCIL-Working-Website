---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Great people doing amazing work is what makes NCIL. Here’s who we are:
{:.center}

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

## Graduate Students
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}

{% include section.html %}

## Undergraduate Students
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}

{% include section.html background="images/banner.jpg" dark=true%}

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

Gone but never forgotten.
These are past lab members who have moved on to other school programs, new jobs, or elsewhere.

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

  image1="images/photo.jpg"
  link1="https://nasa.gov/"
  tooltip1="Cool Foundation"

  image2="images/photo.jpg"
  link2="https://nasa.gov/"
  tooltip2="Cool Institute"

  image3="images/photo.jpg"
  link3="https://nasa.gov/"
  tooltip3="Cool Initiative"

  image4="images/photo.jpg"
  link4="https://nasa.gov/"
  tooltip4="Cool Foundation"

  image5="images/photo.jpg"
  link5="https://nasa.gov/"
  tooltip5="Cool Institute"

  image6="images/photo.jpg"
  link6="https://nasa.gov/"
  tooltip6="Cool Initiative"
%}
