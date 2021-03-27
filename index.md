---
layout: default
name: Socialyte
title: null
---
<style>
.outermwp { 
  position: absolute;
  width: 33%;
  top: 50%;  
  left: 50%; 
  margin-right: -50%;
  transform: translate(-50%, -50%);
  display: inline-block;
  background: transparent;
}
.innermwp {
  transition: transform 0.6s;
  transform-style: preserve-3d;
}
.outermwp:hover .innermwp {
  transition: 0.9s;
  transform: rotate(180deg) rotateX(180deg) rotateY(180deg) translate(-50%, -50%);
}
</style>
<a class="outermwp" href="mailto:socialyte@socialyte.net"><img class="innermwp" src="/favicon.ico" /></a>
