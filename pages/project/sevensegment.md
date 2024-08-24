---
layout: default
permalink: /project/sevensegment
weight: 1
---

# Seven Segment Display
I made this project to emulate [Seven Segment Displays](https://en.wikipedia.org/wiki/Seven-segment_display) inside Roblox. Seven-Segments are usually used to display numbers, as their ability to display readable text is extremely limited.

The Displays I made work using a custom module I wrote. This module allows displays of any length to be generated from any origin. Two basic methods in the module are `:Clear()` and `:All()`, these functions turn every segment of the display on or off respectively. It also has a function for rendering numbers (which gives the option to pad numbers either as spaces or zeros), and rendering text (very limited readability).

## Gallery
![hours:minutes:seconds clock](/images/rgb-clock.png)
This is a clock that showcases the ability to recolor displays. The clock actually ticks and displays the player's local time.

![unix clock](/images/unix-clock.png)
The Unix Clock is a little bit simpler, as it just displays the current unix time (seconds since Dec. 1st, 1970). Unlike the first clock, this one runs on the server and displays the same time to every player.

![new years countdown](/images/new-years.png)
For this project, I used multiple displays stacked on top of each other. This project is a countdown in seconds til the next new year. It also vividly illustrates the poor readability of many text characters in seven-segments.

## Game Links
Here are some links to the projects shown above so you can check them out for yourself:

- [Multi-color Clock](https://www.roblox.com/games/103668598146941/Seven-Segment-Clock)
- [Unix Clock](https://www.roblox.com/games/80340211699540/Seven-Segment-Unix-Timestamp)
- [New Years countdown](https://www.roblox.com/games/125898242454332/Seven-Segment-Countdown-to-New-Years)