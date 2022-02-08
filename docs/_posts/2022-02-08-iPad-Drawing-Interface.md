---
title:  "Using your iPad Pro as a PC Mapping Interface"
date:   2022-02-08 21:33:02 +0000
categories: tutorial
---
Tutorial: Use your iPad Pro as a drawing tablet input for making polylines in QGIS on Windows or Mac  <br><br>

<img src="/assets/images/posts/02-08/iPadPen.jpg" width="50%" height="auto" align="center"/><br>
  Using a pen stylus to draw polylines in QGIS<br> <br>


If you're like me and are tired of manually clicking thousands of polyline vertices when making digital geologic maps, then hopefully this workflow saves you some pain! <br>
In this tutorial I show how you can use your iPad Pro as a drawing input to ease the tedious task of clicking out individual vertices for polylines in QGIS.
<ol>
<li> First, install QGIS on your PC, and EasyCanvas on both your iPad Pro & PC. <a href="http://www.easynlight.com/en/easycanvas/">http://www.easynlight.com/en/easycanvas/</a>

<li> Install the beePen plugin in QGIS. (Plugins>Manage and Install Plugins>search beePen>Install) 

<li> Connect your PC to your iPad with a USB cable. Run the EasyCanvas PC program (EL Display Hub). You should now see your PC's desktop mirrored onto your iPad.

<li> Open QGIS and load up your basemaps. Click the beePen icon on your taskbar, or go to Plugins>beePen. From the beePen plugin menu (by default center bottom window on your screen), create a new layer and name it as you like. Now click the pencil tool on the beePen toolbar and start drawing on your iPad using your Apple Pen or similar stylus. Each time you release your pen a line feature will be created, add a comment or push enter to continue. I find myself switching back and forth from the PC to iPad frequently. 

<li> If your lines are too jagged, you can adjust the smoothing parameters from the beePen plugin window. 


<li> You might need to still do some manual mouse-based editing to properly connect or attribute lines, but I find this process much easier than manually clicking to draw all the lines.

<br><br> Happy mapping! <br> <br> 
 

<img src="/assets/images/posts/02-08/iPadScreen.png" width="50%" height="auto" align="center"/><br>
  iPad Screengrab showing mirrored Windows & QGIS<br> <br>



