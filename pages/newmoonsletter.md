---
layout: page
bodyClass: pathfinders
permalink: /pathfinders/newmoonsletter/
title: Pathfinders Newmoonsletter
description: As the moon completes another orbit around Earth, the Pathfinders Newmoonsletter rises in your inbox to inspire collective pathfinding towards better tech futures.
publish: true
image: /wp-content/uploads/2024/03/pathfinders-newmoonsletter_title.png
hero_title: Pathfinders Newmoonsletter
hero_text: As the moon completes another orbit around Earth, the Pathfinders Newmoonsletter rises in your inbox to inspire collective pathfinding towards better tech futures.
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
  title="Subscribe for moonthly seeds of tech inspiration"
  content="A companion on your pathfinding journey, the Newmoonsletter rises in your inbox under the New Moon – when the nights are darkest – to inspire collective pathfinding towards better tech futures."
  image_position="right"
  under_image="
  <iframe src='https://tethix.substack.com/embed' max-width='480' height='320' style='border:1px solid #EEE; background:white;' frameborder='0' scrolling='no'></iframe>
  "
  bg_color="bg-secondary"
%}
