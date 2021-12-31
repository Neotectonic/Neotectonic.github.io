---
layout: post
title:  "Exporting Orthos from iDar"
date:   2021-12-29 23:33:02 +0000
categories: tutorial
---
In this tutorial I show you how to export a 2D orthographic view of a 3D model produced using the built in iOS laser scanner. This is a common need for paleoseismic excavations, so that a scanned trench exposure can be converted to a 2D figure and annotated for use in a paper. This is surprisingly non-trivial, but it is not a common requirement in the 3D design world, which is more oriented towards AR/VR, gaming, or CAD than for this niche need. 

1. In your 3D scanner app, clean up your model, deleting unnecessary areas. 
2. export as OBJ file, and transfer file to your computer 


<img src="/assets/images/posts/12-29/Katz-crop.png" width="auto" height="auto" align="center"/>

4. Import model into blender (free) Don’t worry that it isn’t displaying the texture. 
5. Under view, select orthographic. Position your view such that you are looking dead on at the trench exposure. Now select the camera and push ctrl + alt + NumPad0 to snap the camera to your current view. Now select the camera in the scene collection, and click the movie camera menu icon (object properties) and change type to orthographic. Adjust the bounding box to cover the trench. 
6. Select Viewport Shading in the top right of the viewing window (sphere icon) to preview your image. 

<img src="/assets/images/posts/12-29/layout.png" width="auto" height="auto" align="center"/>

6. Select the light in the collection.  Click to set the cursor in front of the trench. Now right click and snap selection to cursor. Push F12 to preview render of the trench. Move the light towards or away from the trench as needed to adjust. You can copy paste additional lights and adjust the intensity as desired

<img src="/assets/images/posts/12-29/final.png" width="auto" height="auto" align="center"/>
