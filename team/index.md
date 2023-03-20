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

{% include section.html background="images/banner_joinus.jpg" dark=true%}

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

  image1="images/sshrc-fip-full-color-eng.jpg"
  link1="https://www.sshrc-crsh.gc.ca/home-accueil-eng.aspx"
  tooltip1="SSHRC"

  image2="images/NSERC_FIP_RGB.PNG"
  link2="https://www.nserc-crsng.gc.ca/index_eng.asp"
  tooltip2="NSERC"

  image3="images/DMRF_Logo.svg"
  link3="https://dmrf.ca/"
  tooltip3="DMRF"

%}
