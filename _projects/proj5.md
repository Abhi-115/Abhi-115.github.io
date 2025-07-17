---
title: "16-bit signed-unsigned Booth Multiplier Design"
layout: single
collection: projects
excerpt: "Complete implementation of pipelined 16-bit Booth Multiplier with Power Gating"
category: course
header:
  teaser: "/assets/images/dvlsi_proj1.png"
  #image:  "/assets/images/surge2.jpeg"
tags: [Hardware]
---

In this project as a part of the Digital VLSI Course, we designed a Radix-4 Booth encoded 16-bit controlled signed-unsigned Multiplier using Cadence Virtuoso. The design incorporated Wallace Tree structure to improve efficiency during summation, which in turn was done using multi-bit carry save adders (CSAs). The final addition was performed using a 32-bit Carry Bypass Adder in order to reduce propagation delay of the carry generated during the summation. Finally, in order to reduce the static power consumption, power gating was employed using header and footer sleep transistors. The entire design was implemented as a schematic first in Cadence Virtuoso, and then laid out using the 45nm technology node. The layout was optimised for minimum area, and correspondingly low power. The post layout frequency of operation was 30MHz.

<a href="/assets/images/dvlsi_proj3.png" data-lightbox="gallery" data-title="Top Level Schematic">
  <img src="/assets/images/dvlsi_proj3.png" alt="Top Level Schematic" style="width: 50%; margin-bottom: 1rem; border-radius: 8px;">
</a>
<a href="/assets/images/dvlsi_proj5.png" data-lightbox="gallery" data-title="Partial Product Generator">
    <img src="/assets/images/dvlsi_proj5.png" alt="PP Gen logic" style="width: 50%; margin-bottom: 1rem; border-radius: 8px;">
</a>
<a href="/assets/images/dvlsi_proj4.png" data-lightbox="gallery" data-title="Wallace Tree Structure">
    <img src="/assets/images/dvlsi_proj4.png" alt="Wallace Tree" style="width: 50%; margin-bottom: 1rem; border-radius: 8px;">
</a>
<a href="/assets/images/dvlsi_proj2.png" data-lightbox="gallery" data-title="Pipelining Schematic">
    <img src="/assets/images/dvlsi_proj2.png" alt="Pipeline" style="width: 100%; margin-bottom: 1rem; border-radius: 8px;">
</a>
<a href="/assets/images/dvlsi_proj1.png" data-lightbox="gallery" data-title="Final Layout">
    <img src="/assets/images/dvlsi_proj1.png" alt="Layout" style="width: 100%; margin-bottom: 1rem; border-radius: 8px;">
</a>