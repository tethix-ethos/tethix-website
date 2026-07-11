---
layout: page
bodyClass: pathfinders
permalink: /pathfinders/
title: Pathfinders
seo_title: '%%title%% %%page%%'
description: Welcome, wondering wanderer, eager to explore paths to better tech futures, together. The Pathfinders Newmoonsletter, Full Moon Gatherings, and podcast ran from 2023 to 2025 — the archive is yours to explore.
publish: true
image: /wp-content/uploads/2024/03/featured-img_pathfinders.png
hero_title_top: The Pathfinders
hero_text: |
    The tech industry likes to move fast and break things, starting wildfires left and right.
  
    As responsible firekeepers, we invited wondering wanderers to stop feeding the wildfires. To look around. To look up. To start exploring the paths not so well travelled — together, as Pathfinders.  
  
    The pathfinding adventure ran from 2023 to 2025. The seeds it planted — the Newmoonsletter, the gatherings, the podcast — remain here for you to wander.
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
  
  If you recognize yourself in this description, the paths explored here are yours to keep walking."
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
  title="Moonthly seeds of tech inspiration, 2023–2025"
  content="A companion on the pathfinding journey, the Newmoonsletter rose in inboxes under the New Moon – when the nights are darkest – to inspire collective pathfinding towards better tech futures.
  
  Nineteen moons rose between October 2023 and April 2025. All of them are archived below and on [Substack](https://tethix.substack.com/s/pathfinders-newmoonsletter)."
  image_position="right"
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
  title="Gatherings around the virtual campfire"
  content="Under the Full Moon – when the nights are brightest – Pathfinders packed their exploration backpacks and gathered around the virtual campfire to discuss the lunacy of tech.
  
  The gatherings have ended, but many of the paths they illuminated live on in the [podcast](#podcast) and the [Newmoonsletter archive](#newmoonsletter-archive)."
  image_position="right"
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
  content="In an industry that feels increasingly erratic, we embraced its lunacy with smiles and love.

  Pathfinders synced their monthly reflections and gatherings to the lunar cycle as a reminder of our place in the Universe and a commonality shared across timezones and places we inhabit.

  The moon still rises. We hope that gazing up into the night sky inspires you to dream about different worlds and examine our current world from a different perspective."
  bg_image="/wp-content/uploads/2024/03/stars-background.svg"
%}
