---
layout: post
title:  "Walls that Soak"
date:   2016-04-17 21:17:53
categories: [Art, Sonic]
thumb: "/assets/thumbs/wallt.jpg"
cover: "/assets/projects/wallsThatSoak/overall1.jpg"
permalink: /soak/
---

Walls that Soak is an interactive installation that constructs concrete form out of sensory cues that resemble mental rather than physical conceptions of architecture. Revealing its meaning in layers, the installation exists as a filmic pan of a structure, through which participants obtain hints and generate a tactile understanding of a space. Walls that Soak represents a small, but fully scaled, two story structure of a home, using primarily three elements: interactive sound, a floor plan drawn out on the floor, and hanging fabric.

{: .col-sm-12 .media}
<div class="video-container" style="margin-bottom:40px;"><iframe width="560" height="315" src="https://www.youtube.com/embed/nmEPrDxlEuA" frameborder="0" allowfullscreen></iframe>
</div>

<h1>The Process</h1>
<p>The idea began with the system of representation. Our intension was to simulate a structure that could be discovered by walking through it and listening to the intricacies of the space. We wanted to represent a quintessential structure of home and we settled on representing Leah's childhood home in Cape Breton, Canada. It was both simple enough to be represented in a small space and had enough personality to be excavated through it's audio. We sourced all of the dimensions and a portion of the audio from the house.  </p>
			
<img src="/assets/projects/wallsThatSoak/canada1.jpg" alt="Canada Process" >
<img src="/assets/projects/wallsThatSoak/canada2.jpg" alt="Canada Process" >
<p>Eventually we wanted to represent the structure at full scale, but we started small, by making drawings and mockups.</p>

{: .col-sm-6 }
<img src="/assets/projects/wallsThatSoak/model2.jpg" alt="Model Process" >

{: .col-sm-6 }
<img src="/assets/projects/wallsThatSoak/model3.jpg" alt="Model Process" >

<p>The vision for the sound experience was to create a fully navigable sound space, that would allow each room to have a texture of multiple sounds in different locations. I created two different software applications in C++ using Open Frameworks to make this possible. </p>
<img src="/assets/projects/wallsThatSoak/tracking1.png" alt="Tracking Process" >
<p>The first application uniquely tracked a participant as he or she walked through the exhibition space. It did so by recognizing a pattern of dots on top of the wireless headphones they used to hear the resulting sounds. The application has the capacity to track four individual headphone wearing individuals and tell the left side of the head from the right side of their head. In this project we only used its capacity to identify one of these headphones without taking note of its left right capacity. </p>

<p><a href="https://github.com/crecord/OfTrackingDotPatterns">Click here </a> for more technical details and code.</p>

<img src="/assets/projects/wallsThatSoak/tracking2.jpg" alt="Tracking Process" >
<p>The second application received the location data and transformed it into sound. The application allowed us to create a detailed soundscape of Leah's Cape Breton home. We could enter in a floor plan and assign sounds to each room. Additionally we could create fuzzy regions of sound within each room. These regions could be permanently looping in a set locations or they could occur once and they could even be animated through out space. Ultimately, we used over 50 sound samples tied to different locations in the exhibition in a looping five minute composition. </p>

<p><a href="https://github.com/crecord/OfSoundMapping">Click here</a> for more technical details and code. </p>



		


