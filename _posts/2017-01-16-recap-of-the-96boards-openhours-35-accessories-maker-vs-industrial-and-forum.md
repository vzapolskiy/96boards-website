---
author: linaro
comments: true
date: 2017-01-16 21:36:59+00:00
layout: post
image: /assets/images/blog/OpenHours-02.png
image_name: OpenHours-02.png
link: https://www.96boards.org/blog/recap-of-the-96boards-openhours-35-accessories-maker-vs-industrial-and-forum/
slug: recap-of-the-96boards-openhours-35-accessories-maker-vs-industrial-and-forum
title:
  Recap of the 96Boards OpenHours 35 - Accessories, Maker VS. Industrial and
  Forum
wordpress_id: 19521
Boards:
  - DragonBoard 410c
  - HiKey
category: blog
tags:
  - 64-bit
  - 96Boards
  - aarch64
  - Android
  - ARM
  - ARMv8
  - Breakout
  - bubblegum-96
  - CE
  - Consumer Edition
  - Consumer IoT
  - DB410c
  - debugging
  - dragonboard410c
  - gdb
  - gui
  - HiKey
  - Library
  - Linux
  - Low speed expansion header
  - Open Embedded
  - Open Hours
  - OpenHours
  - Reference Platform
  - rpb
  - sensors
  - UART
---

Welcome to our 35th episode of 96Boards OpenHours.  Last week we had a great discussion about 2016 and all the good and bad that happened over the year.  You can read the blog here:  [https://www.96boards.org/blog/welcome-2017-year-96boards/](/blog/welcome-2017-year-96boards/).  Robert then announced the winner of the 96Boards give-away.  He went on to talk about the next Linaro Connect for 2017 that will take place in Budapest March 6-12, 2017.  96Boards will have many sessions during the week as well as another live broadcast of OpenHours during the event same as we did at LAS16.  We are looking for sponsors if you are interested please visit:  [http://connect.linaro.org/sponsors/](http://connect.linaro.org/sponsors/).  There are many different levels of sponsorships available.  Register now to reserve your spot and don't miss out on this great week of all things engineering - [http://connect.linaro.org/](http://connect.linaro.org/).

Robert then discussed the weekly digest that he is working on putting together and hoped to get more people signed up as well as more ideas for content submitted to the team.  In other news an attendee of the call announced an event that is taking place in Brazil that will focus on a development project on DragonBoard:  http://www.embarcados.com.br .  Winners will be sent to Santa Clara for IOT.

Robert then introduced today's topic which was a discussion on how in the last year community members have stepped up their game in creating a variety of cases, add ons, and mezzanine products.  David then explored the need/possibility of future accessories and assess the value add of industrial style add-ons by giving use-cases and prompting the community for suggestions.  David then talked about some of these creations and the different materials used to create these cases and costs.  Robert and David then discussed the many different examples and showed some of the ones members have built.  The chat below has links to further information about these accessories.

To watch episode 35 go to[ https://www.youtube.com/watch?v=njMXCPLmPT4](https://www.youtube.com/watch?v=VGvJT8xEXvo) or watch below:

{% include media.html media_url="https://www.youtube.com/embed/VGvJT8xEXvo?feature=oembed" %}

**Be sure to join us for next week's OpenHours:  [https://www.96boards.org/](/)**

As always there is a lot of good information and resources that is available in the chat below, this is a great place to get more detailed information mentioned during the call.  Also a while ago in the hangout Robert shared a link to allow people to submit topics or questions for the developers on the hangout.  The link is:[ https://discuss.96boards.org/t/openhours-topic-suggestion/ ](https://discuss.96boards.org/t/openhours-topic-suggestion/)and Robert will take these suggestions and try to incorporate these into future OpenHours.

Please remember, if you get stuck, there are resources to help you through the installation. Feel free to check out the [96Boards forums](https://discuss.96boards.org/), [96Boards wiki](https://github.com/96boards/documentation/wiki), or [Freenode IRC](http://webchat.freenode.net/?channels=%2396boards) channel #96boards (there are many ways to access IRC, this website is one of them). Dig around the wiki, create a new forum thread, and/or post a question in the chat.

**Below is the chat log from the OpenHours session today:**

RW

https://www.96boards.org/blog/welcome-2017-year-96boards/

http://connect.linaro.org/

robert.wolff@linaro.org

---

M

chat members might like to have a discussion here about "how to convince your manager in why you should go to connect"

---

K

where is your sponsorship page?

any levels?

http://connect.linaro.org/sponsors/

---

K

$1M  < $100K < <<<< $250

---

M

Please do not tell your manager what a nice city Budapest is, and what great beer they have....

---

G3

or tell your manager they can tag along

---

M

Depends on who your manager is....if it is Ken Thompson......come on Ken!

---

FP

great point haha

---

RW

http://www.embarcados.com.br

https://www.youtube.com/channel/UCjawhk_W1QnJs3pKIsKLJNg

---

M

Fred, are you going to Campus Party, Brazil?

---

RW

www.twitter.com/96boards

---

DM

https://www.shapeways.com/

---

FP

Maddog, Yes

The Dragonboard 410c contest will start at Campus party

---

RW

https://www.thingiverse.com/

http://www.thingiverse.com/thing:1090288

http://www.thingiverse.com/thing:1692217

---

G3

it would help to look at any success stories where companies have taken these boards and deployed solutions in production environment

---

RW

http://www.thingiverse.com/thing:1424340

http://www.thingiverse.com/thing:1663560

https://www.shapeways.com/

---

KT

I was thinking I might try to use a cast aluminum guitar pedal case - something like: http://www.hammondmfg.com/dwg.htm

---

D

Does boot, but phone app crashes

unplug keyboard, phone app doesn't crash anymore

---

G3

same here

didnt boot 118

---

D

99 is Lollipop, pretty old

---

RW

http://builds.96boards.org/

---

AK

I'd be interested in clarifications about the heat sink functionality of this case (and perhaps a video demo). Does the low-sunk bit of the case touch the SoC+Memory package?

---

G3

I tried it and it didnt build.

boot i mean

---

D

I installed 118 today and the phone app continually crashes.  Unplug the keyboard though, and the crashing phone app messages stop

---

G3

thanks don, will try doing that and see if i get the same

https://www.pactecenclosures.com/ companies like pac tec can make IP rated enclosures with modifications

---

RW

https://discuss.96boards.org

https://discuss.96boards.org/c/products/dragonboard410c/#gsc.tab=0

https://discuss.96boards.org/c/products/hikey/#gsc.tab=0

https://discuss.96boards.org/c/products/bubblegum96/#gsc.tab=0

---

DM

I am about to start a new blog series, adding 1.8v sensors to a 96boards with the goal of an HVAC control system

---

RW

https://discuss.96boards.org/t/no-limited-video-and-audio-playback-on-the-hikey/#gsc.tab=0

https://docs.google.com/spreadsheets/d/1aYNUlGx5J8RmfWrtML4lFJ-7tV8u-3AH_3IaiOlWfoE/edit?usp=sharing

---

MB

how are you going to handle the length of link in putting i2c in different rooms?

---

Click here to join us for [next OpenHours ](/)
