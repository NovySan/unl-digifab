# Week 3 - Laser Cutter; 2D Digifab
## Agenda
- Announcements:
  - Lecture recordings (try and try again)
  - Digital Sketchbooks
  - Configure Rhinoceros Zoo (license)
    - (Rhino is available in the computer lab as well)
- Review HW1 and HW2
- Topics
  - [Intro to Laser Cutter](#intro-to-laser-cutter) (hardware hands-on)
  - [Cutting](#cutting)
  - [Design for Laser Cutter](#design-for-laser-cutter)
- [Homework](#homework)
- [Office Hours this Week](#office-hours)

# Intro to Laser Cutter

Hands-on with our [FSL Muse 3D (Full Spectrum Laser)](https://fslaser.com/fsl-muse-3d-autofocus-desktop-co2-laser-cutter-bundle/):

__1. Laser basics__
- Safety (air filtration; fire safety)
- __ALWAYS__ before you cut: turn on the Water Cooler, Exhaust, Air Assist.
- The Muse has two lasers, actually: an infrared CO2 laser (actually cuts our materials), and a visible light Red laser (for knowing where you are going to cut)
- We also have a 3d camera. This is useful to capture an image of workspace (2D) to lay out a cut on our material. In 3D mode we can do some etching/engraving on irregular and three dimensional materials. That is an advanced topic.

__2. Material choice__
- _Good_ materials for laser cutter:
  - thick papers (card stock, manilla folder, index cards, office paper, watercolor paper, bristol board, vellum)
  - thin cardboard (poster board, matte board, corrugated cardboard - i.e. cardboard boxes)
  - plastic sheets (acrylic, ABS)
  - wood (architectural plywood, balsa wood, thin birch plywood, veneers) 
  - engraving on leather
  - textiles
- _Bad_ materials:
  - anything vinyl (PVC plastic tube and sheet, vinyl decals)
  - polystyrene (i.e. styrofoam, packing peanuts)
- What other materials do you have questions about?

__3. Laser Settings__
- For any given material, we need to find the right power settings. 
- There are three parameters we set: __Speed__, __Power__, __Current__.
  - (see the chart at the bottom fo the page for some starting points for different materials)
- We can do formal tests to find the best parameters. See this [Materials Test](http://laser101.fslaser.com/materialtest) procedure.
  - (we can also do this a little more informally) 
  - Blog post on [Laser Settings for Cutting](http://blog.fslaser.com/experts/muse-workflow-laser-settings-for-cutting)
- Over time, we (as a Center) will come up with our own materials settings that work well with our laser cutter. 
- So, __log your cuts__: (date, time, material, thickness, power settings)
  - (we need this to build our library of materials and settings)

__4. Cut Types__
- Engraving vs Cutting: 
  - __Engraving__: marking patterns into the surface of a material (faster, lower power, can engrave materials like glass, stone that can't be cut through)
  - __Cutting__: cutting through the material. (slow, higher power, smokes/catches fire)
  - The difference is whether you are cutting through the material, or marking the surface.
  - The power of our laser tube (45 Watts) determines what thickness we can cut through. Higher power lasers (65-75W, 100W) can cut through thicker materials. But there are still limits. The fiber laser (Innovation Studio) is a whole different laser type that can cut through 0.25" plate steel, for instance.
- There are three main operations we will do: 
  - __Vector Cutting__: cutting shapes out of materials. **this is the bulk of what we will do**. SVG files. 
  - __Vector Engraving__: using vector art to mark the surface. designs, patterns, cross-hatching. SVGs.
  - __Raster Engraving__: rendering a bitmap on the surface of something, row by row like an old school printer. BMPs.
- In the Muse software (RetinaEngrave), "Cutting" and "Engraving" are both called Engraving. We just choose different power settings. See the chart at bottom of the page.
<img src="https://user-images.githubusercontent.com/1598545/132678369-cbc08f46-2793-48e7-9f08-f020cf8dcfc6.png" width="400px">

__5. Cut demos__
- We will use your HW1. 
- Let's double check/fix our HW 1 and then cut some. 

# Cutting
Full Spectrum Laser has their own engraving software called [RetinaEngrave](https://fslaser.com/re3/).  We will use it from the workstation on the laser table.

1. Create Design
2. Open RetinaEngrave on the workstation. (Desktop Shortcut, or Safari -> `fslca88.local`)
3. Import the design (SVG file). We will use HW1.
4. Place your material in the laser cutter
5. Secure your material (blue tape)
6. Capture workspace (camera)
7. Change your line colors/layer colors, if you need to.
8. Change your scale/placement, if necessary. 
9. Set the engraving properties - __Vector Engraving__ (note, it is all called "engraving" in Muse)
10. Turn on Water Cooler; Exhaust; Air Assist.
11. Run job.

# Design for Laser Cutter

__Simple Laser Cutter Design__
1. Create new file from template. Small objects inches.
2. Drawing in 2d; using layers
3. Optional: Extrude your layers to the thickness of your material, to see what this would look like __as cut__. 
   - (f.ex. for 1/8" birch plywood you would extrude it to something like 0.125" thick. you can use your calipers to check these measurements)
5. Exporting to SVG.

__Tab and Slot Construction__


__Advanced__
- Living hinge construction
  - Kerf Bending Experiments: https://www.martin-breuer.com/kerf-bending-patterns
  - Lattice Hinge Design Workshop: https://futurearchi.org/t/lattice-hinge-design-workshop-starting-from-an-open-source-grasshopper-design/576

![image](https://user-images.githubusercontent.com/1598545/132702764-8225398f-a764-49a5-95e2-77019343fe65.png)
From https://futurearchi.org/t/lattice-hinge-design-workshop-starting-from-an-open-source-grasshopper-design/576

# Homework
- [Exercise 3]

# Office Hours
- Tuesday (9/14) - 12:30-3:15 - Shop hours
- Wednesday (9/15) - 1-2pm

# Reference
- RetinaEngrave Software:
  - [quick reference guide](https://info.fslaser.com/hubfs/Public_Documents/RetinaEngrave%20v3.0%20RefGuide.pdf)  
  - [Video Tutorials](https://www.youtube.com/playlist?list=PL_1I1UNQ4oGa0w55C772Y1mC6F4f3ZcG6)
  - [RE3.0 Manual](https://info.fslaser.com/hubfs/Public_Documents/RetinaEngrave%20v3.0%20Manual.pdf)
- FSL Muse References:
  - [Muse 3D Manual](https://f.hubspotusercontent00.net/hubfs/2882208/MUSE_MANUAL.pdf)
  - FSL Muse specifications, safety documentation.
  - Suggested starting power settings for FSL Muse (do tests and adjust these for your project):
![image](https://user-images.githubusercontent.com/1598545/132598192-898d58a6-ba56-40fc-8e95-18374daada8a.png)
