---
weight: 1000
images:
- /images/ChantTitleCard.jpg
title: The Chant
date: 2022-07-23
tags:
- work # homepage
- archive # all posts
- games
- art
- design
hideExif: true
---

<div class="slider" id="slider">
	{{ range $i, $post := ($.Get "posts") }}
	    {{ partial "slides/slide.html" (dict "disableFullheight" false "ctx" $post) }}
	{{ end }}
	<div id="arrow" class="down-arrow"></div>
	<div class="navigate">
		<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
		<a class="next" onclick="plusSlides(1)">&#10095;</a>
	</div>
	<button onclick="closeSlider()" class="modal-close" aria-label="close"></button>
</div>

## The Chant

A psychedelic survival horror game that focuses on a ritual gone wrong during a spiritual retreat. Published by **Prime Matter** and developed **Brass Token**. My role on this project was working as a **Game Designer**.

### My Work

While a part of this project, I had a hand in a lot of different aspects of the game and had many jobs I was given lead on.
- 

