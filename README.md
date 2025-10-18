# Barnes-Hut N-Body-Simulation

If you are reading this, welcome to my first-ever non-trivial programming project (I am writing this README years after making it).
I would like to speak on behalf of my past self and apologize for the lack of a build system and funky code.

## What is it?

This project is an implementation of a gravitational N-Body simulation in 2D and 3D, using the Barnes-Hut algorithm. I can definitely say I fell in love with programming (and tree data structures) by building this project.

## Features
### Performance
I tried my best to make the simulation perform well. To do so, I used the Barnes-Hut algorithm and leveraged some very sketchy multi-threading. 
If I remember correctly, I was able to get tens of thousands to a few hundred thousand bodies, depending on the accuracy.

### Options Galore
For better or for worse, I expose a ton of options for the user to tweak and mess with, including how the particles are spawned, the G constant, and much more.

### Custom Option Language
With all those options, I needed some way to save them. For some reason, I decided to make my own arcane little "language" to save the options for a simulation.
I could have used a JSON parsing library, but this is much cooler, and I respect past me for it.
