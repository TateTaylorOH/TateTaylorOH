---
layout: page
title: The Adventures of Rickard Calvert
description: Follow the journey of Rickard Calvert, adventurer extraordinaire!
---
# Rickard Calvert
![](https://staticdelivery.nexusmods.com/mods/1704/images/headers/52397_1725415004.jpg)

Join adventurer extraordinaire Rickard Calvert as he treks across Tamriel with nothing but his trusty pocket knife, uncovering lost artifacts and wandering into places he definitely doesn’t belong. It’s all in a day’s work for the greatest adventurer in all of Mundus.

## Rickard Calvert in the Isles of Madness

![](https://raw.githubusercontent.com/TateTaylorOH/TateTaylorOH/main/assets/images/ECSS/Mania04.png)

Follow Rickard as he ventures into the enigmatic Shivering Isles.

<ul>
  {% assign rc_posts = site.posts | where_exp: "post", "post.categories contains 'rickardcalvert'" %}
  {% assign sorted_rc_posts = rc_posts | sort: "order" %}

  {% for post in sorted_rc_posts %}
    <h3>{{ post.title }}</h3>
    {{ post.excerpt | replace: '<img', '<x-img' }}
    <font size="4">
      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">Read more...</a>
    </font>
    <br>
    {{ post.date | date_to_string }} • {{ post.author }}
  {% endfor %}
</ul>

<!-- ## Rickard's Outtakes

<center><a href="https://raw.githubusercontent.com/TateTaylorOH/TateTaylorOH/refs/heads/main/assets/images/RickardCalvert/RickardMelonNose.png"><img src="https://raw.githubusercontent.com/TateTaylorOH/TateTaylorOH/refs/heads/main/assets/images/RickardCalvert/RickardMelonNose.png" 
     width="445" 
     height="250" /></a> <a href="https://raw.githubusercontent.com/TateTaylorOH/TateTaylorOH/refs/heads/main/assets/images/RickardCalvert/RickardAlwaysHasBeen.png"><img src="https://raw.githubusercontent.com/TateTaylorOH/TateTaylorOH/refs/heads/main/assets/images/RickardCalvert/RickardAlwaysHasBeen.png" 
     width="445" 
     height="250" /></a>
     
<a href="https://raw.githubusercontent.com/TateTaylorOH/TateTaylorOH/refs/heads/main/assets/images/RickardCalvert/RickardMexico.png"><img src="https://raw.githubusercontent.com/TateTaylorOH/TateTaylorOH/refs/heads/main/assets/images/RickardCalvert/RickardMexico.png" 
     width="445" 
     height="250" /></a> <a href="https://raw.githubusercontent.com/TateTaylorOH/TateTaylorOH/refs/heads/main/assets/images/RickardCalvert/RickardYeeHaw.png"><img src="https://raw.githubusercontent.com/TateTaylorOH/TateTaylorOH/refs/heads/main/assets/images/RickardCalvert/RickardYeeHaw.png" 
     width="445" 
     height="250" /></a></center>
-->
---
