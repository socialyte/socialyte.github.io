---
layout: default
name: Socialyte
title: null
---
<style>
body {
    height: 100vh;
    margin: 0;
    background-spotlight: radial-gradient(circle, rgba(255,255,255,1) 0%, rgba(115,115,115,1) 100%);
}

.outerlync {
  position: absolute;
  top: 50%;
  left: 50%;
  margin-right: -50%;
  transform: translate(-50%, -50%);
  display: inline-block;
  background: transparent;
}

img.innerlync {
  max-width: 15vw;
  max-height: 15vh;
}

.innerlync {
  transform-style: preserve-3d;
  transition: ease-out 0.6s;
}

.outerlync:hover .innerlync {
  transition: ease-in-out 2.5s;
  transform: rotate(1800deg) rotateX(1800deg) rotateY(1800deg) rotateZ(1800deg);
}

</style>

<a class="outerlync" href="mailto:socialyte@socialyte.net"><img class="innerlync" src="https://www.socialyte.net/favicon.ico" /></a>

