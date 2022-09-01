# Week 2 - Laser Cutter

## Tuesday
- Review [Rhino 2D Basics](#rhino-2d-basics)
- Topics
  - [Intro to Laser Cutter](#intro-to-laser-cutter) (hardware hands-on)
  - [Cutting](#cutting)
  - [Design for Laser Cutter](#design-for-laser-cutter)

### Artist of the Day

<img src="https://images.squarespace-cdn.com/content/v1/56d5c341c6fc0815c1e73ee6/1500147928833-2YFUM1ZPJHUTHDOWKBYL/Crossing+Boundaries+%28Black%29+-+Asia+Society+Shot+6_hr.jpg?format=2500w" width=400>

[Anila Quayyum Agha](http://www.anilaagha.com/crossing-boundaries-black)

## Review

### Rhino 2D Basics
1. Create new file from template. Small objects inches.
2. User interface:
   - Switch between single and quad (four-up) display. 
   - Pan, tilt, zoom in display. 
   - Turning __Grid Snap__ on and off. (To create points that stick to origin, 0.25in, etc.) Try as a text command: Type _Snap_ once to turn it on. Once to turn it off.
3. 2D Primitives
   - [_Line_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/line.htm). 
     - Choose start of line, end of line. 
     - Hold __shift__ key while drawing to make the line orthogonal (Right Angle). [_Ortho_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/ortho.htm)
   - [_Rectangle_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/rectangle.htm)
   - [_Circle_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/circle.htm)
   - [_Polygon_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/polygon.htm)
4. 2D Operations
   - [_Trim_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/trim.htm) uses one object to cut and delete parts of another object.
   - [_Split_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/split.htm) uses one object to cut and split another object.
   - [_Join_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/join.htm) connects objects to form a single object
   - [_Extend_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/extend.htm) lengthens or shortens a curve
5. Organization
   - [Layers](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/layer.htm). [Using layers](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#seealso/sak_layer.htm).
   - [_Group_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/group.htm)
   - [_Ungroup_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/ungroup.htm)
   - [Selecting](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#popup_actions/select_objects.htm). How to Select things with the mouse.
   - Selection Menu
6. Transforms
   - [_Scale_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/scale.htm)
   - [_Rotate_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/rotate.htm)
   - [_Move_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/move.htm)
7. Direct Manipulation
   - Changing objects once you have drawn them. We are dealing with [NURBS](https://wiki.mcneel.com/rhino/nurbs)
   - [_PointsOn_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/pointson.htm)
     - Click and drag to move points. Use transforms (_Move_). 
   - [_PointsOff_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/pointsoff.htm)

## Intro to Laser Cutter

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

## Cutting
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
## Design for Laser Cutter

__Simple Laser Cutter Design__
1. Create new file from template. Small objects inches.
2. Drawing in 2d; using layers
3. Optional: Extrude your layers to the thickness of your material, to see what this would look like __as cut__. 
   - (f.ex. for 1/8" birch plywood you would extrude it to something like 0.125" thick. you can use your calipers to check these measurements)
5. Exporting to SVG.

## Thursday

### Artist of the Day 

![image](https://user-images.githubusercontent.com/1598545/187927860-5f8562d7-a570-4f86-ad8a-f2e61c886b3b.png)

Ben Butler
- https://mymodernmet.com/ben-butler-organic-sculptures/
- https://www.benbutlerart.com/

### Tutorial

__Measuring Thickness__

<img width="543" alt="image" src="https://user-images.githubusercontent.com/1598545/187929511-8a4545b6-dddb-4427-8dcc-b22d8726bd96.png">

- Using calipers. See [Sparkfun: How To Use Calipers](https://www.youtube.com/watch?v=73YJA5giZfs) (youtube link)
- Cutting tests. 

__Tab and Slot Construction__
1. How can we build 3d structure with 2d materials? 
2. Tab and slot construction? (also called finger joints)
3. You need to design 2d parts that have holes (slots), and other parts that have tabs, so that when cut from flat materials you can assemble them into 3d forms.
4. Optional: Extrude your designs to the thickness of the material, to make solides. Assemble these solides in Rhino to mock up your 3d form.
5. Reference (Video Tutorials):
   - Finger joint laser cut box: https://www.youtube.com/watch?v=FBSQGHBpBWg
   - Finger joint tutorial in Rhino with boolean operations: https://www.youtube.com/watch?v=AYxUUSWIRW4

__Advanced 3D Forms__
- Living hinge construction
  - Kerf Bending Experiments: https://www.martin-breuer.com/kerf-bending-patterns
  - Lattice Hinge Design Workshop: https://futurearchi.org/t/lattice-hinge-design-workshop-starting-from-an-open-source-grasshopper-design/576
- Slicing / panelling tools (breaking 3d structure down into 2d components that can be assembled)
- Parametric design for kerfs and 3d structures (grasshopper)

# Homework
- Ideas for [project 1](../projects/project1.md)

# References
- For your reference: [Rhino Learn](https://www.rhino3d.com/learn/?keyword=kind:%20rhino_win) (tutorials)
- [Sketchup to Rhino Cheatsheet](https://static1.squarespace.com/static/585ca81337c5816afcb8d981/t/5c7478b715fcc0b3c46366d7/1551136953876/Sketchup-Rhino+Cheat+Sheet.pdf)
- ![image](https://user-images.githubusercontent.com/1598545/131845474-7ce17921-1ce1-4601-b6ef-96ec6d62a6cc.png)
- - RetinaEngrave Software:
  - [quick reference guide](https://info.fslaser.com/hubfs/Public_Documents/RetinaEngrave%20v3.0%20RefGuide.pdf)  
  - [Video Tutorials](https://www.youtube.com/playlist?list=PL_1I1UNQ4oGa0w55C772Y1mC6F4f3ZcG6)
  - [RE3.0 Manual](https://info.fslaser.com/hubfs/Public_Documents/RetinaEngrave%20v3.0%20Manual.pdf)
- FSL Muse References:
  - [Muse 3D Manual](https://f.hubspotusercontent00.net/hubfs/2882208/MUSE_MANUAL.pdf)
  - FSL Muse specifications, safety documentation.
  - Suggested starting power settings for FSL Muse (do tests and adjust these for your project):
![image](https://user-images.githubusercontent.com/1598545/132598192-898d58a6-ba56-40fc-8e95-18374daada8a.png)
