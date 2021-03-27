---
layout: default
name: Socialyte
title: null
---
<style>
.outermwp { 
  position: absolute;
  top: 50%;  
  left: 50%; 
  margin-right: -50%;
  display: inline-block;
  background: transparent;
}
.innermwp {
  transition: transform 0.6s;
  transform-style: preserve-3d;
}
.outermwp:hover .innermwp {
  transition: 0.9s;
  transform: rotate(180deg) rotateX(180deg) rotateY(180deg);
}
</style>
<a class="outermwp" href="mailto:socialyte@socialyte.net"><img class="innermwp" style="width: 10%" src="/favicon.ico" /></a>
