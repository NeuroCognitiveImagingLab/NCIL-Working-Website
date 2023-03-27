---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Great people doing amazing work is what makes NCIL. Here’s who we are:
{:.center}

## Staff
{% include list.html data="members" component="portrait" filters="role: pi, group: " %}

{% include section.html %}

## Graduate Students
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}

{% include section.html %}

## Undergraduate Students
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}

{% include section.html background="images/20111102_BrainRepair_01.jpg" dark=true%}

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% include section.html %}

## Collaborators
{% include section.html %}

## Partners
{%
  include gallery.html

  image1="images/SURGE/S_Color_horizontal_medium_lightBG.png"
  link1="https://www.surgeinnovation.ca/"
  tooltip1="SURGE"

  image2="images/Ensuring_Full_Literacy_logo.png"
  link2="https://ensuringliteracy.ca/"
  tooltip2="Ensuring Full Literacy (SSHRC Partnership Grant)"

  image3="images/BRC_logo.png"
  link3="https://www.brainrepair.ca/"
  tooltip3="Brain Repair Centre"

  image4="images/IWKLOGO.png"
  link4="https://www.iwk.nshealth.ca/"
  tooltip4="IWK Health Centre"

  image5="images/QEII_logo.svg"
  link5="https://qe2foundation.ca/"
  tooltip5="QEII Health Sciences Centre Foundation"

%}

{% include section.html %}


## Funding
Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html

  image1="images/sshrc-fip-full-color-eng.jpg"
  link1="https://www.sshrc-crsh.gc.ca/home-accueil-eng.aspx"
  tooltip1="SSHRC"

  image2="images/NSERC_FIP_RGB.png"
  link2="https://www.nserc-crsng.gc.ca/index_eng.asp"
  tooltip2="NSERC"

  image3="images/BRC_logo.png"
  link3="https://www.brainrepair.ca/"
  tooltip3="Brain Repair Centre"

  image4="images/Mitacs.png"
  link4="https://www.mitacs.ca/en"
  tooltip4="Mitacs"

%}

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