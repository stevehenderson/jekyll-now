---
layout: post
title: My second post
---


I've been cranking away on getting the Google Project Tango working with an Augmented Reality setup that allows Motion Tracking, Point Cloud data, and a video see-through display.

I wanted to work in Unity, but the Unity SDK for Tango doesn't allow point cloud data collection to share the camera.

So one needs to use java and connect the Tango to a surface view.

I've got it working in this [this repository.](https://github.com/stevehenderson/TangoAugmentedRealityTest2)

TODO:

* Port the example to OpenGL ES 2.0
* Incorporate a lightwegith 3D game engine (maybe [JPCT](http://www.jpct.net) )
