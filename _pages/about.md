---
permalink: /
title: "Home"
author_profile: true
---

I am a Professor in the [Department of Statistics](https://www.des.ufscar.br) at the [Federal University of São Carlos (UFSCar)](https://www.ufscar.br), Brazil.

I enjoy teaching, mentoring students, and helping people develop their ideas.

I also work on probability and statistics, mainly with applications in neuroscience.

<div class="home-art" aria-hidden="true"></div>

<style>
.home-art {
  position: fixed;
  right: 0;
  bottom: 0;

  width: 48vw;
  height: 55vh;
  max-width: 750px;
  max-height: 600px;

  background-image: url('{{ "/images/home-art.png" | relative_url }}');
  background-repeat: no-repeat;
  background-position: right bottom;
  background-size: contain;

  opacity: 0.28;
  pointer-events: none;
  z-index: 0;
}

#main {
  position: relative;
  z-index: 1;
}

@media (max-width: 768px) {
  .home-art {
    display: none;
  }
}
</style>
