---
layout: post
title: Complete the Motion Tracking example
---

OK..I've been working hard on getting an Augmented Reality example going on Tango.  I want to ensure that we can use ALL the features of the Tango--Motion Tracking, Area Learning, 
and Point Cloud / Depth info.

The point cloud algorithm shares the back camera---so to do video see-through AR you need to grab the color pixels from the Tango.  You cannot use
the Android native camera API because the Tango already has hooks in the camera.

So you need to use the connectTabgo() method.  See [this post](http://stackoverflow.com/questions/26771558/getting-color-data-in-java-tango-sdk-or-c-sdk?rq=1))

Well, I've cracked the code on it and have a pretty good simple demo working that is a proof of concept:

https://github.com/stevehenderson/GoogleTango_AugmentedRealityTest_MotionCapture

To do:

  - Calibrate the camera with the display
  - Calibrate the scene with the IMU
  - Double check my rendering pipeline (I think its off)
