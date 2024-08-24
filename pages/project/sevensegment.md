---
layout: null
permalink: /project/sevensegment
---

# Seven Segment Display
I made this project to emulate [Seven Segment Displays](https://en.wikipedia.org/wiki/Seven-segment_display) inside Roblox. Seven-Segments are usually used to display numbers, as their ability to display readable text is extremely limited.

The Displays I made work using a custom module I wrote. This module allows displays of any length to be generated from any origin. Two basic methods in the module are `:Clear()` and `:All()`, these functions turn every segment of the display on or off respectively. It also has a function for rendering numbers (which gives the option to pad numbers either as spaces or zeros), and rendering text (very limited readability).

## Gallery

{% capture carousel_images %}
/images/rgb-clock.png
/images/new-years.png
/images/unix-clock.png
{% endcapture %}
{% include elements/carousel.html %}

## Game Links
Here are some links to the projects shown above so you can check them out for yourself:

- [Multi-color Clock](https://www.roblox.com/games/103668598146941/Seven-Segment-Clock)
- [Unix Clock](https://www.roblox.com/games/80340211699540/Seven-Segment-Unix-Timestamp)
- [New Years countdown](https://www.roblox.com/games/125898242454332/Seven-Segment-Countdown-to-New-Years)