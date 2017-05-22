---
layout: post
title: Project Hexagon
date: 2016-07-08
tags: Unity C# Hobby
---
So this is supposed to be a bigger Post about "Project Hexagon", which started out as "just something using hexagons". The whole project started out as a random world generator featuring Diamond-Square, Cell-Noise and Hydraulic Erosion Algorithms and other fancy things. <!--more-->Back then it looked like this:
<center>
<img src = "{{site.url}}/assets/images/OldMapGen1.png" alt = "Here would be a beautiful Heightmap" style = "width:40%;height:400px">
<img src = "{{site.url}}/assets/images/OldMapGen2.png" alt = "Here would be a colorized Heightmap" style = "width:40%;height:400px">
</center>

As you might see, these are colorized heightmaps drawn onto a hexagon Field. From all the Algorithms my favourite one was Cell Noise, its heightmaps really looks great:
<center>
<img src = "{{site.url}}/assets/images/CellNoise.png" alt = "Here would be a Heightmap using Cell Noise">
</center>

Even though it was a kinda dumb idea to display the maps on Hexagons, I started to like the Idea behind hexagonal Grids. Therefore I've started digging deeper into the matter and switched over from using Sprites to code generated Meshes. That was the time where the Idea of a Hexagonal Turn Based Strategy Game came up, so the next thing I did was adding ~~programmer art~~ wonderful sprites for various Unit types, which would get spawned at Game Start. It would play much like chess, but every Unit had a certain amount of HP and a unique attack pattern. That was quite funny, but not deep enough. The next step was to bring the boring looking 2D Hexagon map to the third dimension whilst also adding a map Editor to further enhance the randomly generated Maps. I love Map Editors! After some tweaking and fighting with code generated normals, it now looked like this:
<center>
<img src = "{{site.url}}/assets/images/HexagonCurrent.png" alt = "Here would be a colorized Heightmap" style = "width:60%">
<br>
I'd say the switch to 3D was a great choice.
</center>

In the latest version, it is now possible for Units to capture Structures and recruit new Units inside them. If anybody would ask me what kind of game it is going to be, my answer would be "some sort of mixture between Final Fantasy Tactics and Advance Wars". Both great TBS Games if you ask me.
The next step would be adding Water Creatures, unique Unit skills and customizable Heros. I can't really wait to see it all come together, but now it is more or less time for a break until October... Exams are coming!