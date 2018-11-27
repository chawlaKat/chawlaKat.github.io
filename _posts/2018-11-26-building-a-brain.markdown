---
layout: post
title:  "Building a Brain"
categories:
---

Welcome, gentle readers!

So. I was right, and I was wrong.

In my last post, I talked about .stl files, and theorized that I needed to convert them to .obj files in order for Unity to use them. This was absolutely correct. I found a .stl to .obj converter online, converted all of the files from Dr. Menier, and got them imported into Unity. I now have a 3D model of the brain, built of thirteen cross sections with lovely amounts of detail. 

However. I also talked about dragging and dropping .tiff files onto the objects, stretching the image over the surface of each object. Technically, this works; I was able to import the 24 images (top and bottom of each cross section, except for the first and last sections) as materials. I was also able to drag a .tiff onto an object. Unfortunately, Unity stretched the image across the entire surface area of that object, warping the coloring into unrecognizable shapes. Only allowing one image per object, Unity would not permit me to provide separate graphics for the top and bottom of each cross section. The next step here is to research into how Unity deals with materials so I can create appropriate images to apply to the entire surface of each item.

In addition to the progress on the model composed of cross sections, I also created a structure-based model. Using Unity GameObjects, specifically spheres and cylinders, I built a (rudimentary) representation of the brain. In this model, the cerebrum and cerebellum are both shown as spheres, and the brainstem is a cylinder. This will allow interaction in the 3D sense, instead of only relying on stacked 2D-style sections. Next, I will create a more sophisticated model by creating custom object shapes for each subsection of the brain, on the level of the temporal and occipital lobes. 

And so, onwards we go, my friends.
