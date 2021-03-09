---
layout: post
title: Sherle Wagner
description: Website and Online Catalog
img: /img/SW/SWshowcase.png
tags: [Web Development |, Ruby on Rails |, Mobile UX |, UI]
---




<div class="col three">
Sherle Wagner is a luxury bathroom fixtures company with a passion for unique and elegant design. My partner <a href="http://wakelankard.com/" target="new">Wake</a> and I were tasked with redoing their <a href="http://sherlewagner.com" target="new">website and online catalog</a>.

<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/SW/SWshowwide.png" alt="" title="display showcase"/>
	
</div>
<div class="col three caption">
	Responsive website with Ruby on Rails, PostgreSQL and Bootstrap
</div>

The goal was to create a responsive site to showcase a fully re-done set of product images and to match the minimalist aesthetic of their newly re-designed print catalog.

The website needed to serve as a product catalog for the sales staff as well as for clients, both private customers & interior designers, so emphasis was placed on browsing and the search function. 

<br> <br>
Creating an elegant way to browse and filter the extensive line of products was important. 
We designed a checkbox-filtering system using AJAX calls and responsive accordion panels.

</div>


<div class="col two">
	<br>
	<img class="col three" src="{{ site.baseurl }}/img/SW/SW_Nav_2.jpg" alt="" title="mockup"/>
		<div class="col three caption">
	An early mockup in Blasamiq
	</div>
</div>

<div > 

	We initially included styles and collections in the top level of the side nav but user testing of our mockups showed that that was too cumbersome and confusing. 
<br><br>
	Style checkboxes were added and featured collections were removed from the main product browsing page.
</div>

<br/>
<div class="col three">
	We imported products as rows from the company's master products spreadsheet by uploading a .csv and assigned filter values such as 'levers' , 'gold', or 'china' as products were added to the database.
<br>
	In the frontend, Jquery handled showing and hiding products based on filter selections.
</div>
<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/SW/filterGif2.gif" alt="" title="filter gif"/>
	<div class="col three caption">
	..
	</div>
</div>
<div class="col three">
To show variety in the higher levels of the products section, we displayed products of each type, such as ‘Fittings’ and ‘Hardware’ broken in preview panels with 5 products from each of their sub-types (like 'sinks' or 'cabinet levers'). 

This way customers can scroll through a section without wading through many pages of a single type of product. Each subtype has an environment image, adding color to each section. 

This was an elegant way to mimic the experience of browsing the print catalog with each section showing significantly more individual products. We arrived at this solution through numerous iterations of paper prototypes and quick and dirty mock-ups.
</div>
<br>
<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/SW/scroll1.gif" alt="" title="scrolling gif"/>
	<div class="col three caption">
	..
	</div>
</div>

<div class="col three">
Each product is available in a wide range of finishes and with a variety of inset china patterns and semi-precious stones. The client provided as many photos of each product arrangement as possible but needed the option to add additional images and manage available inlays and finishes. Images are hosted on Amazon S3 and Rails integration is handled with Paperclip. 

We built a swatch system that displayed images of their selected product arrangement (or a black and white if no image was available) and generated customer inquiries and tearsheets. 
</div>

<!-- prod page img gif / s -->

<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/SW/prodPagechina.gif" alt="" title="china gif"/>
	<div class="col three caption">
	..
	</div>
</div>
<div class="col one">
	<br>
	<img class="col three" src="{{ site.baseurl }}/img/SW/ipadProd.png" alt="" title="ipad product"/>
		<div class="col three caption">
	Product Pages are responsive at multiple sizes.
	</div>
</div>
<br/>
<div>

We created a custom CMS to manage products and finish and inlay options and to provide a wide range of website customization and management. 
The custom CMS is powered by RailsAdmin.
<!-- image of Admin -->
<!-- <div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/SW/___" alt="" title="admin img"/>
	<div class="col three caption">
	..
	</div>
</div> -->
We also created database tables to handle products like shower systems that comprised multiple other products, allowing compilation products of the same style to appear on a single product page with multiple possible arrangements photographed. We also designed an interface to browse component products for each image/arrangement and a management system in the admin section (CMS).
</div>
<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/SW/systemGif.gif" alt="" title="compilation gif"/>
	<div class="col three caption">
	Compilations include links to stand-alone products. Components link to their compilations.
	</div>
</div>

<div class="col three">
Product lines are grouped into 'styles' reflecting period & aesthetic and the product catalog had to emphasize these and show the wide range of custom bathroom styles while minimizing clicks. This was a chance to design a unique look for each collection and to feature the new environment photography. 
We created an image rich landing page for the Collections section, grouping them into styles on with a floating menu and scroll-effects.

Each collection’s unique page represents the design of the print catalogue, with varied sizing and extensive environment photos. We created a system of dynamic image tiles that can be managed through the custom CMS. Image sizes and environment photos can then be customized by the client. Sorting & filtering is handled by JQuery. 
</div>
<br>
<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/SW/colGif.gif" alt="" title="collection gif"/>
	<div class="col three caption">
	..
	</div>
</div>



<!-- <div class="img_row">
	<img class="col two" src="{{ site.baseurl }}/img/6.jpg" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/11.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
	You can also have artistically styled 2/3 + 1/3 images, like these.
</div>
 -->




