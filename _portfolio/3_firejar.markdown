---
layout: post
title: FireJar
description: Location-Based Media
img: /img/fjar/firejar.jpg
tags: [Web Development |, NodeJS + Express |, Mobile UX |, UI]
---


<iframe src="https://player.vimeo.com/video/165600223" width="660" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
FireJar is a mobile web application and API for adding digital time-capsules to specific locations based on GPS location.
Exploring how digital interactions can shape our experience of the world around us, this project invites people to discover content and add to a map of location-based media. The goal of this interactive piece was to use digital interactions to enhance and mediate an experience of locations and spaces in the physical world.

The mobile web application was built using NodeJS and Express with MongoDB and Mongoose. Media uploads are stored with Amazon S3. The location information and map interactions use websockets to send  the devices location and check it against media in the the database.Any files that are in range are then sent back and added.


Content appears white on the map and will turn orange and reveal the image, video or audio as users arrive at it's location.


An early motivation for this project was being able to find videos of street performances, in the locations they occurred, a month or a year later.

<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/fjar/phnbrdg.JPG" alt="" title="example image"/>
</div>


Users log in to upload content and place it on the map. Photos, video, audio and text were all supported and demoed. Log in is not required to discover and view content in map locations.

<div class="img_row">
  <img class="col three" src="{{ site.baseurl }}/img/fjar/addToITP.gif" alt="" title="add note"/>
</div>
<div class="col three caption">
  Prototype: Adding a note and an image from the iPhone gallery to a 'time capsule' at ITP
</div>
<br><br><br><br>
<img class="col one" src="{{ site.baseurl }}/img/fjar/brdgapprch.gif" alt="" title="example"/>



Users can also create Projects that Combine content in different locations,making an experience similar to an audio tour by linking multiple places and pointing where to go next.



To Demo this I created a project that let Brooklyn Bridge visitors discover and listen to Walt Whitman’s poem Crossing Brooklyn Ferry as they crossed.
We placed stickers along the bridge to prompt people to go to the fire jar page, find the recordings and listen. 


The verses are strung along the route so that at walking speed, it will queue the next verses as they are picked up (Lat/Long proximity). I made sure to have a seamless playback to minimize the need to look at or use a mobile device. Leaving a response was encouraged though and comments and pictures/videos were uploaded and added to the FireJar project.

<br><br>

<iframe src="https://player.vimeo.com/video/165600283" width="660" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<br><br>
Potential applications for this project include: <br>
-A Low-cost  solution for traditional audio/multi-media tours for institutions like museums and historic sites.<br>
-Locative media or guerrilla art about an areas Music,  Culture. <br>
-Tourism or local guide showing events like festivals or decorations year-round.<br>
-Story-telling, fiction and non-fiction, as location based podcasting can tap into the feeling of a setting to tell immersive stories.



