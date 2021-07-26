---
title: Digital Graffiti Wall
description: Graffiti Simulator
date: 2015-06-30 00:00:00
featured_image: '/images/graffiti/graf2.jpg'
tags: [Physical Computing |, Experience Design |, Installation |, Processing]
---

<iframe src="https://player.vimeo.com/video/114297732" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<p><a href="https://vimeo.com/114297732">Digital Grafitti Wall</a> on Vimeo.</p>

Digital Graffiti Wall is an interactive installation that was exhibited in the ITP winter show in 2015. The piece invites users to create a piece of graffiti art on a wall by using a wireless spray-paint can controller to ‘paint’  through a live projection. The spray-paint can wirelessly communicates with an XBox Kinnect and a computer running the custom painting program and updates the projected animation.

<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/images/graffiti/can.gif" alt="" title="controller"/>
	
</div>
<div class="col three caption">
	The Bluetooth Controller has a green light on the nozzle, which the the Kinnect tracks for position.
</div>






Controls on the can allow the user to change color and ‘brush’ size and to switch between drawing and writing modes. 
In writing mode the program uses a handwriting analysis API to find written words and then overlays them in exciting graffiti fonts.
<div class="img_row">
<img class="col one" src="{{ site.baseurl }}/images/graffiti/graf1.jpg" alt="" title="graffiti piece"/>
<img class="col one" src="{{ site.baseurl }}/images/graffiti/tag21.jpg" alt="" title="graffiti piece"/>
<img class="col one" src="{{ site.baseurl }}/images/graffiti/tag1.jpg" alt="" title="graffiti piece"/>
</div>
<div class="col three caption">
 Digital Graffiti pieces from the installation at the ITP Winter Show
</div>
<br>
A main priority for this piece was to enable visitors to create convincing graffiti art. This drove us to include the handwriting analysis function, built with MyScript's api, and also to project onto a plain brick wall, as opposed to a custom surface that could include embedded sensors. 
We used Twilio to let visitors text or email their paintings to within the program.

<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/images/graffiti/setup.jpg" alt="" title="graffiti gif"/>
	<div class="col three caption">
 the display setup
</div>
<img class="col three" src="{{ site.baseurl }}/images/graffiti/graf2.gif" alt="" title="graffiti gif"/>
</div>
The piece was well received and we are currently re-imagining it as a more accessable digital graffiti game package.


