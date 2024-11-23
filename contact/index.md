---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our group is part of the Genomics Division at the Faculty of Biosciences and Aquaculture of Nord University. We are located in spectacular natural settings above the Arctic Circle in Bodø, Norway.

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
  link="[https://www.google.com/maps](https://maps.app.goo.gl/X8kKLQNWWuP1JHTcA)"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/IMG_7580.jpg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
