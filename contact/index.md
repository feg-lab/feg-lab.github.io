---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our group is part of the Genomics Division at the Faculty of Biosciences and Aquaculture at Nord University. We are located in stunning natural settings above the Arctic Circle in Bodø, Norway.

{%
  include button.html
  type="email"
  text="jukka-pekka.verta@nord.no"
  link="jukka-pekka.verta@nord.no"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/X8kKLQNWWuP1JHTcA"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
