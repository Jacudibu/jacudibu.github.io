---
layout: post
title: Tech Nick meets Technic
date: 2016-12-11
tags: Unity C# Innoactive Work
---
Normally I don't like posting about work related Stuff, but this is something I've wanted to talk about as its both funny and dangerous Topic.
A few Weeks ago, the new "Saturn Connect" in Cologne opened. It's called Connect because it focuses on newer Media and also contains some Demos of them. One of them was a VR-Soccer Experience I've created whilst working at Innoactive, combining a GearVR with a Kinect2.

As part of the opening ceremony, Saturn's Advertisement Celebrity Antoine Monot Jr., also known as Tech Nick, put on the VR Goggles, kicked, wanted to run after the ball - but instead collided head-first with the TV. You can see a Video of it over here on YouTube:
<center><iframe width="560" height="315" src="https://www.youtube.com/embed/y8M49fHWanM?t=9s?rel=0?ecver=1" frameborder="0" allowfullscreen></iframe></center>
This was definiately no marketing gag, as the TV broke and he got hurt a little.


First of all, it's a sign that VR seems to work - espeacially with untethered VR Goggles, such as Samsung's Gear VR, people quickly get immersed and forget their surroundings.
But what's more important than that is a specific learning I've made: as VR developers, we should always keep safety in mind. Espeacially when we expect our users to walk around with a Headset on top of their head. For example, in our App we now display a HUGE Stop sign in front of the user when he moves forward too much. Gladly as far as I know there where no more accidents ever since.
The HTC Vive handles that kind of good with those transparent Walls it shows you once you get close to the borders of the tracking space.

But still - what happens, when the game supposes you to walk backwards? How can we make sure, that there's nothing (even if it's just a wall) the user can bump into? That's something even the Vive does currently not tell its users. If you don't want to break the immersion, maybe vibration or something on the back of the headstrap may be a way. Every other solution that comes to my mind right now would kind of disrupt gameplay, which also isn't that great. 