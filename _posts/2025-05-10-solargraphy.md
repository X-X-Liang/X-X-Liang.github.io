---
layout: post
title: "Capturing Time: A Four-Month Solargraphy Experiment"
date: 2025-05-10 12:00:00
description: Bridging theoretical ray optics and real-world observation through an extreme long-exposure pinhole camera
tags: photography optics
categories: beyond-the-lab
thumbnail: assets/img/solargraphy_positive.jpg
citation: false
featured: true
images:
  compare: true
  slider: true
---

When introducing the fundamental concepts of ray optics in my *Photonics I* lectures, the pinhole camera (camera obscura) always serves as the perfect starting point. It brilliantly illustrates that light travels in straight lines. However, rather than simply showing standard textbook diagrams of inverted trees and rays passing through an aperture, I wanted to bring this abstract concept to life with a real, physical demonstration. 

This motivation led me to [Solarcan](https://solarcan.co.uk/), a beautifully simple, ready-to-use pinhole camera designed for extreme time exposures.

### The Deployment: 137 Days of Sunlight
To capture the changing trajectory of the sun from winter to spring, I deployed the Solarcan outdoors, strapped securely to a waterpipe in Lübeck, on **Christmas Eve (December 24, 2024)**. 

The camera quietly sat there, enduring rain, wind, and frost, continuously absorbing light until I finally harvested it on **May 10, 2025**—more than four months later!

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/solargraphy_1.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/solargraphy_2.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/solargraphy_negative.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/solargraphy_positive.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>

### The Physics: How It Works
At the heart of this experiment is pure ray optics. The Solarcan contains no lenses, no digital sensors, and no moving parts. It relies entirely on a precision-drilled microscopic pinhole. 

Because the pinhole blocks all but one ray per object point from reaching the image space, it creates an inverted image on the photographic paper lining the inside of the can. While this optical setup naturally wastes a significant amount of light—and introduces diffraction artifacts—it results in a nearly infinite depth of field. For this specific experiment, the extremely small aperture is actually an advantage: it restricts the photon flux so severely that the light-sensitive paper can be exposed for months without completely washing out.

### The Aesthetics: A Meteorological Footprint
Taking out the light-sensitive paper after four months is a thrilling moment. The raw image is color-inverted, requiring digital scanning and inversion to reveal the final masterpiece.

<img-comparison-slider>
  {% include figure.liquid path="assets/img/solargraphy_negative.png" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/solargraphy_positive.jpg" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>

The resulting image is more than just a photograph; it is a visual diary of Lübeck's weather and orbital mechanics over a third of a year. 

This stunning parabolic solar arc tells a distinct story:
* **The Arcs:** The lowest arcs were captured in late December near the winter solstice, while the highest arcs trace the sun's path as it climbed higher into the spring sky in May.
* **Solid Lines:** Each continuous, unbroken line traces the sun’s path across a fully clear day.
* **Dashed Segments:** These indicate partially cloudy skies, where passing clouds momentarily blocked the light.
* **The Voids:** Large gaps in the arcs correspond to days of overcast or stormy weather that blocked the sunlight entirely.

This solargraphy project is a beautiful reminder that sometimes the most profound scientific visualizations don't require complex numerical simulations or advanced microscopy—just a simple pinhole, a sheet of photographic paper, and the patience to let time do the rest.
