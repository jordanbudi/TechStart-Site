---
title: 360 Extensions
section_title: Extensions
type: unit2
layout: docs
parent_section: unit2
order: 6
---
<hr>

How does a 360 camera magically covert a two-dimensional (2D) image into one that looks three-dimensional (3D)?  All digital cameras use a camera lens and a digital sensor to collect light rays from the world.  Your eyeballs, for example, are really good wide-angle lenses and capture up to 130-degrees of the world at once.

<div style="text-align:center">
	<img src="/images/docs/360_images/FOV.png" width="50%" height="50%">
	<br>
	<strong>The human eye can look up about 60 degrees and down about 70 degrees for a total field of view of 130 degrees.</strong>
</div>

Your Ricoh Theta camera uses two 180-degree lenses and combines them to create one 360-degree image. Here's an example of what the images look like before being combined.

<div style="text-align:center">
	<img src="/images/docs/360_images/theta_example_frame.png">
	<br>
	<strong>Each camera basically captures one half of the world around the camera. </strong>
</div>

The camera then uses computer software to combine the images in a process called **stitching**.

<div style="text-align:center">
	<img src="/images/docs/360_images/theta_example_stitched_frame.png">
	<br>
	<strong>Software in the camera combines the camera images into one. </strong>
</div>

But there's still a problem. The image looks stretched. This is similar to most world maps you have seen. In both cases, the top and bottom of the images are stretched.

<div style="text-align:center">
	<img src="/images/docs/360_images/Equirectangular_projection_SW.jpg">
	<br>
	<strong>The world is also stretched when flat. </strong>
</div>

We can fix the problem by wrapping the images onto spheres. Here's an example of what the process would look like to turn a flat image of the earth into a globe.

<div style="text-align:center">
	<img src="/images/docs/360_images/Dymaxion_2003_animation_small1.gif">
	<br>
	<strong>A flat image can be wrapped into a sphere. </strong>
</div>

Once the image is wrapped, the user gets to choose where on the sphere to look.  No more worrying about what correct Instagram angle to capture - just collect a whole scene with one click of the Ricoh Theta S and then let the viewer decide where to go!