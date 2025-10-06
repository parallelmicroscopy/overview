# overview

These pages describe software and hardware for building your own <b>Random Access Parallel (RAP)</b> microscope. This type of microscope is also called a <b> Multiscope</b>.

### concept

A conventional modern microscope has an objective lens focused on each sample, and a collecting optic (i.e. a tube lens) that refocuses the light onto your eye or camera. One strategy for imaging many different samples would be to have many microscopes, each with its own sample; but this means you need a camera for every microscope. The approach used here is to instead construct a *parallel* microscope. The parallel microscope is conceptually like an an array of individual microscopes, with the difference that all share the same collecting optic and camera.  The system also includes a switchable light source (an array of LEDS), so samples can be illuminated, imaged by the camera, one-at-a-time. Using a fast camera and LED array, we can image samples quickly enough to effectively make measurements from many samples in parallel. The system can capture an entire 24-well plate at full resolution in under 0.1 seconds.

<img width="1126" height="373" alt="image" src="https://github.com/user-attachments/assets/25f0a2c5-f09a-4eb3-b6a0-7a827926e4a1" />



<br>
<br>
The original open-access paper is here:

https://elifesciences.org/articles/56426

Ashraf M, Mohanan S, Sim BR, Tam A, Rahemipour K, Brousseau D, Thibault S, Corbett AD, Bub G. <b>Random access parallel microscopy</b>. Elife. 2021 Jan 12;10:e56426.

### open source hardware and software

An open-source 24 well version can be built using a mix of 3D printed parts and commercially available optics, optomechanics and cameras.<br>

For **hardware** see: https://github.com/parallelmicroscopy/24-well-RAP-hardware<br>
For **software** see: https://github.com/parallelmicroscopy/RAP-software

The hardware and software are rapidly evolving, so please check with [gil.bub@mcgill.ca](mailto:gil.bub@mcgill.ca) before starting your build.

### labs

The following labs have built their own versions of the microscope:

- https://gil-bub.lab.mcgill.ca/
- https://www.corbettlab.com/
- https://www.gla.ac.uk/schools/physics/staff/carolinemuellenbroich/#researchinterests

Several additional labs are actively involved in aspects of the microscope's development:

- https://www.flc-lab.com/
- https://apps.ualberta.ca/directory/person/komarova
- https://www.bmp.ds.mpg.de/authors/stefan-luther/
- https://coplweb.ca/membres/simon-thibault/
- https://www.strath.ac.uk/staff/mcconnellgailprof/

### teaching / design

Two senior undergraduate desgign teams in the University of Madison-Wisconsin are working on the next generation RAP microscope. Check this page and https://seniordesign.me.wisc.edu/ for updates.

### commercial version

If you want to purchase a commercial parallel microscope instead of building your own, Cairn Research (http://www.cairn-research.co.uk)
has a great one. Contact sales@cairn-research.co.uk.



