---
layout: post
title:  "A Study in Paint"
categories:
---

Welcome, gentle readers!

My teammates and I had a great run yesterday, and we're definitely getting to know Unity even better. We spent a good chunk of time learning about .obj files, and then about using .stl and .tiff files. 

Regarding .obj files: I now understand that they represent objects (yeah!). These files that look like a random, excessively long list of numbers actually contain data for constructing 3-dimensional shapes. In an .obj file, you can find data for vertices, faces, and normal vectors. What Unity does with this information is it plots each vertex (point), and then uses the faces and normal vectors to construct the surfaces outlined by those points. They play nicely with Paint 3D, as we found out -- just open the .obj file using that program, it will show the model of your object. To add an .obj to a Unity project, we found out that the file can be dragged and dropped directly into Unity's 'Asset' window to include it with the rest of the project assets. To use it, just add that object to the scene. 

We spent quite a while getting to this point, under the assumption that we had .obj files to import. This...was not quite the case. Our work will definitely still be useful, because Dr. Meneir has .obj files for us down the road, but the files she had sent us recently were in fact .stl and .tiff files. 

So we started playing around with those, too.

.stl files are 3D graphics files similar to .obj files; they also construct full-volume objects. They also work in Paint 3D, and are Paint's default file type for 3D objects. However, Unity does not directly accept .stl files. The next step is researching this a little more, and probably finding a .stl to .obj converter. I look forward to getting these files loaded because the ones we have to work with are the brain cross-sections we're going to use! I thought we would need to build the cross sections from scratch as individual mesh components, but Dr. Meneir has just made our job much easier.

The .tiff files contain data from MRI scans, and from what we can tell, they're textures. So, once we get the cross-section objects working, we'll be able to drop these textures onto their corresponding slices, and voila! Brain!

And so, onwards we go, my friends.
