---
title: Fanfair Mobile App Design
date: 2022-03-01 00:00:00
description: Product design for musicians' networking app
featured_image: '/images/fanfair/ff_screens1_2.png'
tags: [Product Design |, Mobile App |, UX]
---
<style>
  .light {
    background-color: #f4f4f5;
  }
  .single {
    padding: 20px 0;
  }

  @media only screen and (max-width: 1024px){
    .light {
      background-color: rgba(0,0,0,0)
    }

  }

  .img_small {
    max-width: 75%;
    margin: 0 auto;
}

</style>

![](/images/fanfair/ff_profile_t.png)

<h3> Music industry-focused social app for networking and gaining fans</h3>

<strong>My role:</strong> Product Design, UX/Ui design, visual design

My team at Warecorp worked with <a href="https://www.fanfairapp.com/">Fanfair</a> to create a new beta version of their mobile app. We re-designed existing prototypes and added new functionality as we iterated on their product vision. The beta version of Fanfair is available on <a href="https://apps.apple.com/us/app/fanfair-grow-your-audience/id1610189757">the App Store</a> and for Android.

<hr>

<div class="light">
<p>
  <br>
<strong>What is Fanfair?</strong> <br>
</p>
<p>
Fanfair seeks to solve one of the major career challenges that music artists face:
expanding their social media fanbases to attract labels and opportunities. They need to reach new listeners who will become active fans. <br/>
<br/>
Fanfair’s solution is to connect similar artists to each other and help them reach each other’s followers (which they call ‘fansharing’). This way both artists can grow their fanbase. 
<br/>
They set out to create a platform that achieves this and needed a new mobile app MVP. That’s where we came in. Our challenge was to take an app MVP project that had been abandoned and create a working app that delivered on the core value proposition and get it in the hands of users on a short timeline. 
<br/>
<br/>
</p>

</div>

<strong>Starting Point</strong>

On the Design side we received: 
- Existing user research and competitor analysis
- A visual prototype with some of the key screens (and many gaps)
- Some visual assets: logos, icons and photo treatments

The dev team received a code repo from a previous version of the app.

<br/>
### Understanding the Problem

We launched a discovery phase with the Fanfair team to refine the product vision, define the MVP feature set and create a development timeline. During this phase we reviewed the existing assets and did a deep dive with them into their existing research, hypothoses and value proposition. 

This meant reviewing their interview findings and market research summaries and also doing interviews with the team about their ongoing prototyping process.

**Research:** 

They had analyzed competitors, conducted interviews of likely users and developed some basic user personas.


They had also recruited artists as app beta testers and had tested their value-proposition with in person events where they connected artists and had them shout each other out on social media to reach new followers.

<br/>
<br/>
<div class="img_row img_small">

<img style="" src="{{ site.baseurl }}/images/fanfair/ff_banner_screen.png"  alt="" title="steps"/>
</div>
<br/>

<strong>Main Takeaways:</strong>

**-** Artists are excited to connect and willing to publicize each other. They understand that reaching active, engaged fans of their style of music is vital to furthering their careers.

**-** Artists are interested in a solution for this challenge even after they are fairly established in their career. Connecting with other artists and reaching new fans is a continuing effort and passion.

**-** Artists are excited about platforms that can help them with the business side of their careers.

**-** Fansharing works best when it is simultaneous: I post your content to my fans while you post my content to yours. Artists are interested in a streamlined process, not proposing/setting up each agreement and waiting for the favor to be returned. 

<br/>
<br/>

<div class="light">

  <br/>
  <br/>
  
  <div class="img_row img_small">

<img style="" src="{{ site.baseurl }}/images/fanfair/ff_steps_screen.png"  alt="" title="product banner"/>
</div>
<p>
<h3>Solution & Product Vision</h3>
</p>

<p>
During discovery we had identified main challenges and the unique value proposition and defined what success looks like by framing user needs and business goals.
</p><p>
We arrived at some user-centered focus areas that would guide the MVP:
</p><p>
<ul>
  <li>Connections</li>
  <li>Community/content</li>
  <li>Fansharing</li>
</ul>

</p><p>
We also defined some business needs that would inform the approach to creating value in these areas: 
</p><p>
<ul>
  <li>Official Fanfair content/updates</li>
  <li>Gathering key user data</li>
  <li>Time on platform</li>
  <li>Brand aesthetics</li>
</ul>

<br/>
<br/>
</p>
</div>

**Defining the MVP**

We built from the main focus areas in defining the feature set.

Connections: 
- Profile
- Search
- Connect/Accept 
- Chat

Community/Content: 
- Media gallery
- Feed
- Updates(from fanfair)

Fansharing: 
- Invitations
- Content Selection/Pre-flight
- post to external account (Instagram)

We also had to consider app store requirements such as content moderation at this stage.

<br/>

<div class="light">
<p>
  <br/>  
<strong>Designs</strong>
</p>

<p>
Moving into the design phase, we identified key user stories and I created userflows, wireframes and high fidelity interactive prototypes, refining them with the client and the dev team at each stage. Staying aligned was vital as we were looking at a lot of functionality for this MVP and needed to actively balance the scope and development timeline with the main value proposition at this stage.
</p>
<br/>
<br/>

<div class="img_row img_small">

<img style="" src="{{ site.baseurl }}/images/fanfair/ff_dash_wireframe.png"  alt="" title="product banner"/>
</div>
<br/>
<br/>
<div class="img_row img_small">

<img style="" src="{{ site.baseurl }}/images/fanfair/ff_protoflow.png"  alt="" title="product banner"/>
</div>
<br/>
<br/>


<p>
<strong>Solving Design Challenges</strong>
</p><p>
I designed the information architecture around a five icon bottom nav and a tab-style top-nav for related screens–such as notifications and chat.
</p><p>
I designed the profile and media manager to be simple and intuitive.
</p><p>
we created a social-style feed, a notifications screen and chat functionality.
</p><p>
We designed a fansharing experience with minimal steps and a focus on collaboration. It clearly visualizes the system state for both parties as the posts are proposed, updated, approved and posted to Instagram. 
<br/><br/>
</p>

<div class="img_row img_small">

<img style="" src="{{ site.baseurl }}/images/fanfair/ff_xpost_t.png"  alt="" title="x-post"/>
</div>
<br/>
<br/>

<p>
<strong>Design Challenge Example</strong>
</p><p>
Our first focus area was the signin and setup stage and it presented some unique challenges. 
</p><p>
This app needed to be linked to a facebook business account in order to post to instagram. This meant sign up would have an extra, unfamiliar step and require certain configurations to be completed outside the app.
</p><p>
We also needed to get users to add important profile information once signed in. This meant nudging them towards completing a setup process that would let them get the most from the app while limiting the amount of hurdles they had to clear before seeing and experiencing how the app could create value for them.
</p>
<br/>
<br/>
<div class="img_row img_small
">

<img style="" src="{{ site.baseurl }}/images/fanfair/ff_userflow_1.png"  alt="" title="userflow showcase"/>
</div>
<br/>
<br/>
<p>

Ultimately we designed a process that: 
-presented simple, defined steps, conveyed forward movement ( through animated transitions), and used priming/persuading techniques with icons conveying the value proposition. 
-gathered basic profile information during setup
</p><p>
To manage the complexity of the facebook account setup we added a video introduction from the founder to explain and provide reassurance and we made sure that users could explore/experience the app without a fully linked instagram account.

</p>
<br/>
<br/>
<br/>
</div>
<div class="img_row">

<img style="" src="{{ site.baseurl }}/images/fanfair/ff_login.png"  alt="" title="display showcase"/>
</div>
<br/>

<strong>Conclusion & Takeaways</strong>


The app was completed, tested and approved on the app store on a tight timeline to fit with Fanfair’s rollout schedule and the development team did a great job to make that deadline. 
One of the most exciting things about this project was watching the first round of users onboarding as soon as the product went live.
Having the app in the hands of users is an exciting time but due to the nature of our partnership we did hand this project over after the app went live.

Fanfair was able to use this product to move to the next phase of their rollout- validating their value proposition, fundraising and building partnerships in the music industry. 

Some important lessons from this project:

- Don’t underestimate how difficult it can be to get an app approved on a platform, even when it meets all the requirements.
- Component libraries are almost always worth the upfront investment. And Figma has incredible features for them.
- Legacy frontend code can present surprising challenges on the design side, especially for planning.

<br/>
<br/>
<div class="img_row">

<img style="" src="{{ site.baseurl }}/images/fanfair/ff_feed_t.png"  alt="" title="feed"/>
</div>
<br/>
This app MVP has an impressive feature set including a social feed, chat funcionality and a dashboard for managing ongoing fanshares as they are proposed, approved and posted. Designing and prototyping these flows presented interesting challenges and opportunities. <br/>
<br/>
<br/>