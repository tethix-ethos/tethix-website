---
layout: page
bodyClass: pathfinders
permalink: /pathfinders/
title: Join Pathfinders
seo_title: '%%title%% %%page%%'
description: Welcome, wondering wanderer, eager to explore paths to better tech futures, together. Subscribe to the Newmoonsletter and gather around the virtual campfire with other Pathfinders.
publish: true
image: /wp-content/uploads/2024/03/featured-img_pathfinders.png
hero_title_top: Looking for Pathfinders
hero_text: |
    The tech industry likes to move fast and break things, starting wildfires left and right.
  
    As responsible firekeepers, we invite you to stop feeding the wildfires. To look around. To look up. To start exploring the paths not so well travelled. And to join the Tethix pathfinding adventure as a Pathfinder.  
  
    We're not looking for heroes. This is a call for all wondering wanderers, eager to explore paths to better tech futures, together.
hero_image: /wp-content/uploads/2024/03/pathfinding.svg
---

<div class="container pb-6">
  <div class="row justify-content-center text-center">
    <div class="col-lg-4 pb-1">
      <a class="button button-pathfinders" href="#new-moon" role="button"><img src="{{ '/images/icons/tethix-mark-black.svg' | relative_url }}"> Read the Newmonsletter</a>
    </div>
    <div class="col-lg-4 pb-1">
      <a class="button button-pathfinders" href="#full-moon" role="button"><img src="{{ '/images/icons/tethix-mark-yellow.svg' | relative_url }}"> Join a Full Moon Gathering</a>
    </div>
    <div class="col-lg-4 pb-1">
      <a class="button button-pathfinders" href="#podcast" role="button"><img src="{{ '/images/social/podcast.svg' | relative_url }}" style="filter: brightness(0) saturate(100%) invert(17%) sepia(61%) saturate(3073%) hue-rotate(269deg) brightness(98%) contrast(103%);">Listen to podcast</a>
    </div>
  </div>
</div>


{% include section-with-image.html 
  title="Are you a Pathfinder?"
  content="A Pathfinder is a curious soul eager to exercise their moral imagination. To explore the complex dance between technology, society, and collective wisdom.  
  
  In a world overflowing with conventional thinkers, a Pathfinder seeks to uncover overlooked perspectives, embody problem-spaces and foster discussions that lead to actionable insight for the betterment of humanity and our planet.  
  
  If you recognize yourself in this description, join our pathfinding adventure with other curious souls."
  image="/wp-content/uploads/2024/03/pathfinder.svg"
  image_position="left"
  bg_color="bg-light"
%}

{% include section-plain.html
  bg_image="/wp-content/uploads/2024/03/pathfinders-newmoonsletter.png"
%}

{% capture new-moon-title %}
<img src="{{ '/images/icons/tethix-mark-black.svg' | relative_url }}" width="48" height="48"> Pathfinders Newmoonsletter
{% endcapture %}
{% include section-ethos.html
  id="new-moon"
  title_top=new-moon-title
  title="Subscribe for moonthly seeds of tech inspiration"
  content="A companion on your pathfinding journey, the Newmoonsletter rises in your inbox under the New Moon – when the nights are darkest – to inspire collective pathfinding towards better tech futures."
  image_position="right"
  under_image="
  <iframe src='https://tethix.substack.com/embed' max-width='480' height='320' style='border:1px solid #EEE; background:white;' frameborder='0' scrolling='no'></iframe>
  "
%}

{% capture new-moon-content %}
Missed a moon? Browse the archive below or on [Substack](https://tethix.substack.com/s/pathfinders-newmoonsletter) to explore previous seeds of inspiration.

{% include newmoonsletters.html limit="7" %}

<a href="{{ '/pathfinders/newmoonsletter/' | relative_url }}" class="button">Browse all issues</a>
{% endcapture %}

{% include section-plain.html 
  id="newmoonsletter-archive"
  title="Newmoonsletter Archive"
  content=new-moon-content
  bg_color="bg-light"
%}

{% include section-plain.html
  bg_image="/wp-content/uploads/2024/03/pathfinders-full-moon-gathering_full-width.png"
%}

{% capture full-moon-title %}
<img src="{{ '/images/icons/tethix-mark-yellow.svg' | relative_url }}" width="48" height="48"> Full Moon Gathering
{% endcapture %}
{% include section-ethos.html
  id="full-moon"
  title_top=full-moon-title
  title="Gather around the virtual campfire with other Pathfinders"
  content="Pack your exploration backpacks and join us around the virtual campfire under the Full Moon – when the nights are brightest – to discuss the lunacy of tech."
  image_position="right"
  under_image="
  <iframe
    src='https://lu.ma/embed/calendar/cal-j48AAPj374qdYLD/events?compact=true'
    max-width='480'
    height='320'
    frameborder='0'
    style='border: 1px solid #FFDE03; border-radius: 4px;'
    allowfullscreen=''
    aria-hidden='false'
    tabindex='0'
  ></iframe>
  "
%}

{% capture podcast-buttons %}
<a href='https://tethix.substack.com/s/pathfinders-podcast' class='button button-air button-podcast'><img src="{{ '/images/social/headphones.svg' | relative_url }}">Substack</a>
  <a href='https://podcasts.apple.com/us/podcast/pathfinders-podcast/id1743178489' class='button button-air button-podcast'><img src="{{ '/images/social/podcast.svg' | relative_url }}">Apple Podcasts</a>
  <a href='https://open.spotify.com/show/5XQxIqCjSZGF2CfwchcqJw' class='button button-air button-podcast'><img src="{{ '/images/social/spotify.svg' | relative_url }}">Spotify</a>
  <a href='https://overcast.fm/itunes1743178489/pathfinders-podcast' class='button button-air button-podcast'><img src="{{ '/images/social/overcast.svg' | relative_url }}">Overcast</a>
  <a href='https://www.youtube.com/playlist?list=PLZdlb58pgf1MJ726pBswq6rRjM-1Ywg5k' class='button button-air button-podcast'><img src="{{ '/images/social/youtube.svg' | relative_url }}">YouTube</a>
  <a href='https://api.substack.com/feed/podcast/2057093/s/121030.rss' class='button button-air button-podcast'><img src="{{ '/images/social/rss.svg' | relative_url }}">RSS</a>
{% endcapture %}
{% include section-ethos.html
  id="podcast"
  title="Listen to Pathfinders Podcast"
  content="As the moon starts waning, tune into a meandering exploration inspired by the seeds planted in the Newmoonsletter and the paths illuminated during the Full Moon Gathering."
  image_position="left"
  image="/wp-content/uploads/2024/04/pathfinders-podcast.png"
  under_image=podcast-buttons
%}

{% include section-plain.html 
  title="Embracing the lunacy of tech"
  content="In an industry that feels increasingly erratic, we embrace its lunacy with smiles and love.

  Thus, we invite all Pathfinders to sync our monthly reflections and gatherings to the lunar cycle as a reminder of our place in the Universe and a commonality we share across timezones and places we inhabit.

  As we ponder the celestial movements in tech together, we hope that gazing up into the night sky inspires you to dream about different worlds and examine our current world from a different perspective."
  bg_image="/wp-content/uploads/2024/03/stars-background.svg"
%}
