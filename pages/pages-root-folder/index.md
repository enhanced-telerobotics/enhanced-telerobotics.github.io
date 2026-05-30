---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: page-fullwidth
header:
  image: "cover-splash.png"
  background-color: "#0A304E"
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<h2>
<em>"We create robotic systems that help people perceive what is hidden, understand what is complex, and perform what is difficult."</em>
</h2>

<h3>The Enhanced Robotic Interfaces and Experiences (ERIE) Lab at Case Western University develops intelligent robotic systems that help people perceive, understand, and perform cognitively demanding physical tasks. We combine data-driven and model-based machine perception, human-centered feedback, and adaptive autonomy to augment human capabilities in healthcare, remote operations, and other complex work environments.
</h3>

<br>
<img src="/images/ERIE_Concept.png" alt="ERIE Lab Research Concept">


## Recent News

{% include list-posts entries='3' category='news' %}

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
