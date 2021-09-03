---
title: Digital Graffiti Wall
description: Graffiti Simulator
date: 2015-06-30 00:00:00
featured_image: '/images/graffiti/graf2.jpg'
tags: [Physical Computing |, Experience Design |, Installation |, Processing]
---


<h3>Interactive graffiti installation with custom wireless controller, handwriting analysis and digital paint program</h3>

<br/>

This interactive piece invites users to create graffiti art on a brick wall through a live projection. The spray-paint can wirelessly communicates with an XBox Kinnect and a computer running the custom painting program and updates the projected animation, including paint drips. 


<div class="gallery" data-columns="2">
<img  src="{{ site.baseurl }}/images/graffiti/can.gif" alt="" title="controller"/>

<img  src="{{ site.baseurl }}/images/graffiti/setup.jpg" alt="" title="setup"/>
<img class="col three" src="{{ site.baseurl }}/images/graffiti/graf2.gif" alt="" title="graffiti gif"/>
</div>
	


Controls on the can allow the user to change color and ‘brush’ size and to switch between drawing and writing modes. 
In writing mode the program uses a handwriting analysis API to find written words and then overlays them in exciting graffiti fonts.
<div class="gallery" data="columns:3">
<img class="col one" src="{{ site.baseurl }}/images/graffiti/graf1.jpg" alt="" title="graffiti piece"/>
<img class="col one" src="{{ site.baseurl }}/images/graffiti/tag21.jpg" alt="" title="graffiti piece"/>
<img class="col one" src="{{ site.baseurl }}/images/graffiti/tag1.jpg" alt="" title="graffiti piece"/>
</div>

<br>
A main priority for this piece was to enable visitors to create convincing graffiti art. This drove us to include the handwriting analysis function, built with MyScript's api, and also to project onto a plain brick wall, as opposed to a custom surface that could include embedded sensors. 
We used Twilio to let visitors text or email their paintings from within the app.
One major learning was that experienced taggers would always shake the "can" very hard as soon as they had it in their hand.

<br>
<iframe src="https://player.vimeo.com/video/114297732" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

<br>


