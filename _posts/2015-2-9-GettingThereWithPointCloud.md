---
layout: post
title: Getting there with Point Cloud example
---

I have the Point Cloud example working.

[Click here for the repository](https://github.com/stevehenderson/GoogleTango_AugmentedRealityTest_PointCloud)


I spent a substantial amount of time working through an issue with the color camera being underexposed.
You can read about it [here:](http://stackoverflow.com/questions/28402718/dark-google-tango-camera-surface-when-using-depth-information)

Lessons learned so far:
 
 - The camera needs a bunch of light.
 - You can select the FishEye camera by using camera ID 2 in the setSurface method!
 
To do:

  - Integrate an OpenGL scene graph manager
  - Create the annotation activity..the cadet team will work with this.  Need a good structure
    that reads off of and stores to the sql database.  Is there a nifty interface library we can use here?
    
    