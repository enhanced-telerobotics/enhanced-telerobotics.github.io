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

<h1 style="text-align:center;"> ERIE lab is actively recruiting for PhD students for Fall 2023! Please see the TEAM page for more details. </h1>
<br>
<br>
<h3>The Enhanced teleRobotic Interfaces and Experiences (ERIE) Lab at Case Western University seeks to research new approaches to integrate multimodal sensing, multisensory feedback, and data-driven methods to improve human performance in teleoperator systems.</h3>


## Recent News

{% include list-posts entries='3' category='news' %}

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
