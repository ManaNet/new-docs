---
layout: default
title: Timely Anime Images
nav_order: 2
has_children: true
permalink: /timely
---

## :star: Timely Images
Mana has a set amount of timely images features that servers can opt-in to bring in timely *(configurable, default: every 80 minutes)* anime images like Waifus or
Yuri images that many likes.

## :gear: General Command Format
All of these timely images share the same command format (`command_name [bind/filter/unbind/status/speed/help]`) with each options definition being:
- **bind**: This is used to bind the feature onto the specific channel where you ran the command.
- **unbind**: This is opposite of `bind` in which it unbinds the feature from the channel, stopping images from being sent.
- **status**: This is used to check the status of the feature *(Yuriverse/WaifuWorld)*.
- **speed**: This is used to configure the speed of the images being sent. *(`20 minutes`, `40 minutes`, `60 minutes`, `80 minutes`, `120 minutes`, `240 minutes`)*
- **filter**: This is used to configure the filter level of the images with the default being **EXTREME**. *(`No filter (REQURES NSFW CHANNEL)`, `Medium filter`, `Extreme (default) filter`)*
