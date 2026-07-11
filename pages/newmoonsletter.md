---
layout: page
bodyClass: pathfinders
permalink: /pathfinders/newmoonsletter/
title: Pathfinders Newmoonsletter
description: From October 2023 to April 2025, the Pathfinders Newmoonsletter rose under each New Moon to inspire collective pathfinding towards better tech futures. All nineteen moons are archived here.
publish: true
image: /wp-content/uploads/2024/03/pathfinders-newmoonsletter_title.png
hero_title: Pathfinders Newmoonsletter
hero_text: From October 2023 to April 2025, the Pathfinders Newmoonsletter rose under each New Moon to inspire collective pathfinding towards better tech futures. All nineteen moons are archived here.
hero_image: /wp-content/uploads/2024/03/pathfinders-newmoonsletter.png
---

{% assign sorted_issues = site.newmoonsletters | sort: "date" | reverse %}
<section class="blog-posts-list pb-8">
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2 g-3">
      {% for issue in sorted_issues %}
        {% include newmoon-card-list.html %}
      {% endfor %}
    </div>
  </div>
</section>

{% include section-plain.html
  bg_image="/wp-content/uploads/2024/03/pathfinders-newmoonsletter.png"
%}

{% include section-ethos.html
  title="Moonthly seeds of tech inspiration, 2023–2025"
  content="A companion on the pathfinding journey, the Newmoonsletter rose in inboxes under the New Moon – when the nights are darkest – to inspire collective pathfinding towards better tech futures.
  
  No new moons will rise, but the seeds keep. The full archive also lives on [Substack](https://tethix.substack.com/s/pathfinders-newmoonsletter)."
  image_position="right"
  bg_color="bg-secondary"
%}
