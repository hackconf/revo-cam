# RevoCam

_An open-source 360˚ photogrammetry capture system_

Motion Photogrammetry for Surveying
============================================

[Photogrammetry](https://en.wikipedia.org/wiki/Photogrammetry) is the science of making measurements from photographs. Using photogrammetry, we can create 3D models (of things, places, or people) from photographs, and embed them in stories. This allows you to create immersive visualizations for surveying purposes.

There are two basic variations that this software and rig can help you create:

-   3D rendering of an object
-   3D rendering of an environment or room



When should you use it?
------------------------------------

It takes some time to be able to assemble your photos into a 3D model, so it is not uncommon to devote 2-3 full days to capture, process, and render assets.  Some ideas for things that you could reconstruct in a model:

A monument, a rare artifact, a crime scene, an automobile, a jail cell, a cave, a living room, a construction site, or any place where giving interested parties a chance to look around would add to the story.


What doesn't work?
-------------------------------

:warning::skull: **Warning!  Overheating may occur over 1.5 Mbps**

Field tests show this unit can get _very_ hot when pushed beyond its limits  See the chart below for more information.

![overheating-over-1.5](https://cloud.githubusercontent.com/assets/3477155/17794785/791f2088-6580-11e6-9bd4-954243fa2e81.png)

**Excessive Movement**

Objects that move excessively while you are capturing the scene or object may be distorted or may disappear from reconstruction
altogether.

Some surfaces are really difficult to capture. Smooth bright walls, reflective surfaces, and windows will disappear. If you
really need to photograph such surfaces, it's recommended that you cover them with a light porous material.

Capturing video:
-------------------------------

Whether you're filming an object or an environment, the basic principles are the same: you want to get a lot of footage with a
lot of overlap, from a variety of distances and angles.  You need both movement and overlap to produce a rendering.  Skip down if you want to see a diagram of the photo process.

**Movement**

What you need to do is move around the room so that your body isn't in the same place each time you take a new picture. You should
take a step forward or back to zoom in or out: using your camera's zoom function will reduce the quality of the rendering. So don't zoom, move your body to take pictures from different depths. The variations in depth and angle and camera position are what allow our 3D rendering engines to generate a profile of the physical space or the object.

You might have some experience taking photos for a panorama: that is exactly the wrong thing to do for photogrammetry. Definitely do not stand in one place and take a bunch of pictures without moving around. You have to move.

**Overlap**

The images in your photos should overlap a lot. You want 60-70% overlap. It will feel like a lot while you’re taking the pictures. You
are going to take a lot of photos. Way more than you think you need.

More Photo Guidelines:
===================================

It is sometimes possible to create a good reconstruction with fewer photos. Haley Campbell had a chance to visit with [Jeremy Bentham’s Mummified Head](https://www.buzzfeed.com/hayleycampbell/this-is-what-dms-are-for) last fall she took 17 photos, very few of them from the back or above. The head would have been a great subject for a 3D reconstruction so we tried
taking the photos that she did take and feeding them to Autodesk Memento.  The resulting rendering is pretty intense, especially if you zoom in. Note, the detail is very intense when you zoom in. Not everyone actually wants to see that: <https://skfb.ly/OoHQ>

With a more photos from the top and rear of the head, we could make a complete rendering.

Physically move the camera closer or further back instead of zooming in and out on the camera. Don't move any objects during the
photography process, or else it may appear distorted or disappear in the reconstruction. Make sure each photograph has 60%-70% overlap with the images taken before and after it.

The stars and arrows in the image below represent the direction and placement of the camera throughout the space. The photographer
usually stood with the nearest wall to her back, photographing towards the opposite walls and surfaces, as indicated by the arrows emanating from the stars. The notable exception is found at the bottom right corner of the screen, where she took photos inside of her closet, then rotated 90-degrees and began taking photos of the rest of the room.

