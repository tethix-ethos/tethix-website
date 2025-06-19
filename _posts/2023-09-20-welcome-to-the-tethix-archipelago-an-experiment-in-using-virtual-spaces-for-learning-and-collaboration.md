---
layout: post
permalink: /air/welcome-to-the-tethix-archipelago-an-experiment-in-using-virtual-spaces-for-learning-and-collaboration/
title: 'Welcome to the Tethix Archipelago: an experiment in using virtual spaces for learning and collaboration'
description: The story of how and why we developed an entire pixel-based virtual world in Gather that we now use as our office and learning playground.
author: alja
date: 2023-09-20 09:19:50 -0000
last_modified_at: 2024-08-05 11:19:17 -0000
publish: true
pin: false
image: /wp-content/uploads/2023/09/feature-img_Tethix-Archipelago.png
categories:
- Air
tags:
- archipelago
- collaboration
---
Let me tell you a secret: in almost two years of working and playing together, I've never met any of my fellow Tethix firekeepers in person!

As wonderful it would be to sit around an actual campfire with Mat, Nate, and our other collaborators from down under, I can't justify the carbon cost of getting on a plane from Europe to Australia. Plus, this challenging set up across timezones – and seasons! – gives us the opportunity to experiment with our belief that we need diversity and collaboration across borders to tackle the complex challenges of this century. We can't keep defaulting to hopping on a plane to learn from each other. Learning together is crucial, but **we have to embrace more sustainable ways of connecting** , and here is where collaborative technology can help us.

Our [long-term vision](https://tethix.co/our-vision/) is to create a virtual space where diverse people can play and learn together to imagine rainbow mirrors that will reflect paths to more equitable, just futures of human thriving that respect planetary boundaries. Which means that we have to think outside the usual Zoom boxes when it comes to collaborating and learning together.

And so today I'd like to **take you behind the pixels of the Tethix Archipelago** , a place you're likely to visit when setting up a meeting with us. The Archipelago is our office, our learning playground, and the beginning of our long-term vision. It has helped us feel closer as a team and created a shared sense of space among us despite over 16 thousand kilometers and 8–10 hours that separate us.

![](/wp-content/uploads/2023/09/Gather_Tethix_Archipelago-Tethix_Cafe_team_meeting.png)Meeting with fellow Tethix firekeepers in our virtual tea garden in the Tethix Archipelago

_Note: for a more immersive experience, you can[watch a video version](https://www.youtube.com/watch?v=dAdv1goEZJs) of this blog post on YouTube._

## **The evolution of the Archipelago as a virtual place**

Before I take you on a tour of the Archipelago, I'd like to tell you a bit about its history.

The Tethix Archipelago emerged from the Challenge Based Learning[pilot we did in March last year](https://tethix.co/earth/tethix-pilot-challenge-journey-report-pre-launch-and-week-1/). For the pilot, we designed a unique collaborative online learning experience in tech ethics and used[Mural](https://mural.co/) collaborative whiteboards and visual storytelling to situate the learning journey in a fictional world: the Tethix Archipelago. The Archipelago consists of four islands that emerged from the four essentials skills of the Challenge Based Learning journey: collaboration, exploration, practice, and reflection. (You might also recognize these from our[Elemental Ethics](https://tethix.co/elemental-ethics/) framework.)

Mural turned out to be a great tool for collaboration and live session guidance, but it didn't really convey a sense of place. Clicking on a link in a Mural to visit the next leg of your journey just doesn't feel like traveling, especially when you're trapped in the same little Zoom box during every live session.

So we started exploring tools that could help us convey a sense of space and discovered[Gather](https://www.gather.town/) and[WorkAdventure](https://workadventu.re/), among others. These tools offer **two-dimensional virtual collaborative spaces where you can walk around a space with your avatar** and have proximity-based conversations by using your microphone and camera.

After some exploration, we started building the Archipelago in Gather and WorkAdventure, as both of these tools make it easy to build custom maps. To build the world we envisioned, I learned how to build 32x32 pixel maps in[Tiled editor](https://www.mapeditor.org/) using Gather's excellent[mapmaking public tile set](https://github.com/gathertown/mapmaking) and[resources](https://support.gather.town/hc/en-us/articles/15910430385172-Custom-Map-Overview), and even created custom art assets in[Aseprite](https://www.aseprite.org/) when needed.

In the end, we decided to focus development on Gather because the overall user experience is a bit more polished. But I also have a soft spot for WorkAdventure as an open-source alternative that is being built in France and is quite developer-friendly with its[map scripting API](https://docs.workadventu.re/map-building/scripting.md). For instance, I built a cozy Travelers' Inn in WorkAdventure, where you can get a cup of coffee from the innkeeper thanks to a tiny JavaScript and check the iframe noticeboard for messages from fellow travelers.

![](/wp-content/uploads/2023/09/WorkAdventure_Tethix_Archipelago-Travelers_Inn.webp)The Travelers' Inn prototype built in WorkAdventure

The good thing is that maps designed in Tiled can easily be used in both WorkAdventure and Gather. With Gather, there are just a couple of extra steps involved in defining tile effects such as impassable tiles, spawn points, portals, and more in their browser-based Mapmaker tool, and to add any special interactive objects.

![](/wp-content/uploads/2023/09/Tiled-Gather-mapmaker-Tethix-Cafe.png)Behind the scenes: building the Archipelago maps in Tiled, using Gather Mapmaker to add tile effects and interactive objects in rooms

After a couple of iterations, the Archipelago in Gather we now use daily was finally ready to receive its first visitors about a year ago. And while it was initially created as a virtual training ground prototype, it came to mean so much more to our team.

## **A tour of the Archipelago in Gather**

The Archipelago we've built in Gather consists of several rooms, connected by portals. When you first enter the Archipelago, you land on a simple world map with the four islands. The islands are now connected by bridges, so you don't need a boat to get around. As you walk around, you can learn more about each island by getting close to its symbol and pressing X on your keyboard to open a note with a bit of lore.

![](/wp-content/uploads/2023/09/Gather_Tethix_Archipelago-map.png)The Archipelago world map is the default landing spot

But the world map is just the entry point of the Archipelago. By walking to a portal, you can now explore two locations in the Archipelago: the **Tethix Café in Zorya, and the Tethix Office in Practicalia**.

The Tethix Café is a prototype of a meeting space we developed for Zorya Ethics Camp – a collaborative ethics journey for product teams. We're also using it as our main meeting place. And even though we have a cozy café with a collaborative whiteboard at our disposal, we all prefer to meet in the outdoor area we've named the tea garden.

![](/wp-content/uploads/2023/09/Gather_Tethix_Archipelago-Tethix_Cafe.png)The cozy Tethix Café with its adjacent tea garden

From the Tethix Café, you can visit the Ethical Clearing, another demo space we built as part of the Zorya Ethics Camp offering. In the Ethical Clearing, your team can sit around a campfire as you gradually explore how you relate to your values and learn to write actionable pledges.

![](/wp-content/uploads/2023/09/Gather_Tethix_Archipelago-Ethical_Clearing.png)The Ethical Clearing was designed to help teams discover shared meaning and transform it into actionable pledges

When you're ready to explore other places in the Archipelago, head over to the map portal in the tea garden to return to the main map. From there, you can visit the Tethix Office in Practicalia.

Instead of building a boring office with cubicles – it never rains in Gather, so there's no need for walls and roofs over our heads! – we envisioned the Tethix Office as a cozy experience at the beach. Our individual offices match our personalities and interests – Nate's office is still under construction, but will be added soon – and we also have a shared space to talk about our roadmap.

![](/wp-content/uploads/2023/09/Gather_Tethix_Archipelago-Tethix_Office.png)The Tethix Office reflects our personalities and interests

In line with our[codesign principles](https://tethix.co/codesign-principles/), we prefer playing together to just showing and telling, so the whiteboard with our roadmap is actually a secret portal to a living prototype of our vision for the ETHOS Garden. Initially, our ETHOS app will[live in your Slack](https://tethix.co/fire/day-in-the-life-of-a-responsible-firekeeper-your-journey-from-installing-to-embodying-ethos/), but eventually, we see the Garden becoming your office. A virtual place where you meet and get work done, and experience a multisensory reflection of how your actions and pledges nurture your team's values or principles.

![](/wp-content/uploads/2023/09/Gather_Tethix_Archipelago-ETHOS_Garden.png)Our vision for the ETHOS Garden as a living office space that reflects your team's responsibility practice

## **The benefits of sharing a virtual space**

You might be thinking: this is cute and all, but is this Archipelago all games and play? Well, playfulness is a big part of why we're experimenting with these game-like worlds; we know that play helps us learn better and can unlock our imagination. But there's much more to it than just millennial nostalgia for pixel graphics.

As already mentioned, Gather allows us to build a sense of place, both inside rooms and between them. And **a sense of place helps with learning and memory encoding**. Historical records[show](https://artofmemory.com/blog/method-of-loci/) ancient Greeks using the _method of loci_ or memory palaces, a technique for improving memory encoding and retrieval, and humans have been developing other mnemonic techniques based on spatial relationship for much longer than that. We're physical beings, uniquely equipped to understand space, whether physical or represented by pixels.

In Zoom meetings, we never get to share space. We're imprisoned in our respective video boxes, and breakout rooms are not rooms but just a different collection of boxes. Sure, Teams has[Together Mode](https://www.microsoft.com/en-us/microsoft-teams/teams-together-mode) and Zoom has[Immersive View](https://support.zoom.us/hc/en-us/articles/360060220511-Using-Immersive-View-in-meetings-and-webinars#h_01H64NKS0R32SHTJ7C6TYXZPSC), both of which place participants in a shared virtual place. But I haven't seen anyone using it, have you? Honestly, I have no desire to watch myself stitched into a boring auditorium, with a glitchy green screen effect that makes it glaringly obvious we're not in fact in the same space.

And yes, Gather does require you to make a personal connection with the bundle of pixels that represents your avatar in the pixel world, but most people get it pretty quickly. The ability to edit the appearance of your avatar when you enter a Gather space also makes for a great icebreaker during our meetings. (Especially when it makes people a minute or two late to the meeting because they want to get their avatar right.)

Obviously, avatar customization and walking around is a bit more intuitive for those of us with gaming experience, but the learning curve is not steep due to the simplicity and constraints of the 2D world.

**Simplicity makes Gather more accessible and sustainable** than a fully immersive virtual world that requires specialized equipment or state-of-the-art computer graphics. You can even access Gather through a mobile web browser, and the combined size of the PNG files that are used for the Tethix Café map is just 79 KB.

Yes, extra bandwidth is used for the video and audio feeds, but the shared virtual place actually has a surprisingly small footprint – probably smaller than many of today's bloated websites and definitely smaller than fully immersive 3D virtual worlds.

Plus, the simplicity of pixel graphics makes it relatively easy to build new maps and experiment with different approaches. And I say this as somebody with experience building in virtual worlds like Second Life and 3D games in Unity.

Speaking as a Second Life veteran, I can also tell you that complex avatar customization and getting used to walking– or even flying – in a 3D space remains a big adoption hurdle to this day. But the experiences I had in Second Life back in 2007 did teach me a lot about designing for virtual spaces and how virtual spaces can support profound bonding experiences. I don't regularly keep in touch with people I met in Second Life 16 years ago, but whenever we do meet again – either in virtual or physical spaces –, it feels like running into long-lost friends. We shared experiences in those virtual spaces and created lasting memories.

So even though we can teleport and do other magical things that are not (yet) possible in the physical world, virtual spaces are still spaces that work best when they respect features of physical spaces our bodies are intimately familiar with. You can easily tell when something is off in a pixel world and breaks your immersion. It feels weird if you can walk through a wall. You get annoyed when somebody's avatar lands on your avatar's head.

This **physicality of virtual spaces also encourages more human-centric design practices**. For instance, it's waaay too easy to pack 25 people in a Zoom meeting, but building a table in Gather that sits 25 would quickly make you rethink the size of your meeting. Technically, it is possible, it will just feel weird, and you'll likely choose a different layout – or provide several areas for smaller groups, which is the approach we took in the Tethix Café.

For instance, in our tea garden, we have tables of different sizes to accommodate different group sizes. When it's just Mat, Nate and me, we usually sit at the small table, but move to the medium-sized table when there's four or six of us total so that we don't have to sit on each other's heads. Leaving a meeting is interesting as well because you can just walk away from the meeting table and head over to the office for a private follow-up conversation.

And instead of communicating in links, we can now say “Let's meet in the tea garden for a quick chat!” – and it just feels different. We all have a mental image of the space and know where we need to go. Yes, ultimately we're still clicking on a link and joining with our mic and camera (along with any technical difficulties that come with that), but we get to share a table together or sit around a campfire. We're inhabiting a space together, with our camera feeds just an add-on.

The main thing I wish Gather did better is background sounds. Currently, you can add objects with sounds, such as a campfire or water fountain, but the volume controls are clunky. WorkAdventure is more flexible in this regard. One of my favorite virtual meeting spaces outside the Archipelago is a garden I built in WorkAdventure with birdsong playing in the background on a loop. Hearing birds singing[relaxes our minds and bodies](https://www.theguardian.com/environment/2019/may/04/birdsong-antidote-to-stressful-lives-dawn-chorus-day) – birds only sing when they feel safe, so hearing them sing feels reassuring for us – and offers a great space for creative discussions. I hope to be able to bring birdsong to our Gather tea garden soon for a more immersive experience.

## **Walk the Archipelago with us – or build your own!**

Now, our current Archipelago in Gather is just the tip of the iceberg of what we believe virtual spaces – call them metaverse if you like – can offer in terms of improved learning and collaborative experiences. Well-designed spaces help conversations flow more freely, and they are not necessarily built with bricks, especially if we want to encourage diverse collaboration across timezones.

**And we'd love to show you our Archipelago in pixel person** , whether it's for a meeting or a workshop we organize for you. We're also happy to help you figure out how you can bring your own Archipelago – or any other type of geographical configuration that fits your needs better – and improve your flow of ideas.

![](/wp-content/uploads/2023/09/alja-gather-avatar-wave.png)
