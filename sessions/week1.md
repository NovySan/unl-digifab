# Week 1 - Introduction, Overview, Hands-On

## Monday
- Introductions
- Innovation Studio Orientation
- Review Syllabus
- [Lecture 1: Context and Overview](https://docs.google.com/presentation/d/1wZe4Y-v-qv1fI5xNWKBqZGWpz57f6yS_R98hfc4AVRU/edit?usp=sharing)
- Requirements:
	- [ELEGOO UNO Project Super Starter Kit with Tutorial and UNO R3 Compatible with Arduino IDE](https://www.amazon.com/gp/product/B01D8KOZF4?ref=ppx_pt2_dt_b_prod_image)
- [Set up Rhino 3D](#set-up-rhino-3d)
- [Rhino Basics](#rhino-basics)

### Set up Rhino 3d

Install [Rhinoceros](https://www.rhino3d.com/). We have a license for Rhino 8. It uses the Zoo server.

- follow these steps (for Windows): https://www.rhino3d.com/en/features/administration/zoo/#setting-up-rhino-for-windows
- or these steps (for Mac): https://www.rhino3d.com/en/features/administration/zoo/#setting-up-rhino-for-mac
- and enter this information for the zoo server: **its-cemalicense.unl.edu**  
	- <img src="https://user-images.githubusercontent.com/1598545/186644741-11696636-c79e-4d3c-8044-84b81838b571.png" width=300>

### Rhino Basics

  - UI: controls, commands, display modes, view, model units ([interface basics tutorial](https://www.rhino3d.com/learn/?query=kind:%20jump_start%20tag:%20interface,rhino&modal=null), [selection basics tutorial](https://www.rhino3d.com/learn/?query=kind:%20jump_start%20tag:%20selection)) 
  - 2d operations: line, rectangle, trim, circle, dimension
  - transforms: scale, rotate, move
  - operations: split, join, trim, extend
  - organization: layers, groups

- [Robert's excellent video tutorial again](https://drive.google.com/file/d/1AzgcXUiILhfRRCqnAntPxxSZ7xRO9Szj/view?usp=sharing)

### Example Stencil

<img width="600" alt="image" src="https://user-images.githubusercontent.com/1598545/189884689-a2ca1e56-3e37-41f0-86d4-5501d9b19a31.png">

Rhino example: [lines_curves.3dm](../examples/lines_curves.3dm)

- Homework
	- [Watch Robert's excellent video on Rhino 2D basics](https://drive.google.com/file/d/1AzgcXUiILhfRRCqnAntPxxSZ7xRO9Szj/view?usp=sharing)
	- Practice, practice, practice

## Wednesday
- [Laser Cutter Training](#laser-cutter-training)
- [Rhino 2D Basics](#rhino-2d-basics)
- [Artist of the Day](#artist-of-the-day)

## Intro to Laser Cutting

Hands on with the Epilog at Innovation Studio

- Epilog Dashboard for laser operation (TAKE NOTES!!)
- TAKE NOTES.
- Video record with your phone if needed
- Check out the SOP manual.

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

### Example File 2D Basics

<img width="600" alt="image" src="https://user-images.githubusercontent.com/1598545/189883552-117aa5e6-15f9-41ba-83cb-5f5bd18673de.png">

Rhino file: [basic_drawing](../examples/basic_drawing.3dm)

## BONUS:The Muse Laser Cutter at CEMA

Below are the basics for our [FSL Muse 3D (Full Spectrum Laser)](https://fslaser.com/fsl-muse-3d-autofocus-desktop-co2-laser-cutter-bundle/) at the Carson Center but are applicable to almost all laser cutters:

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

### Discord Setup
Please share your discord handle here (so I can add you to our digifab group): [https://forms.office.com/r/zwL9eaWD3a](https://forms.office.com/r/zwL9eaWD3a)

### Artist of the Day

<img src="https://user-images.githubusercontent.com/1598545/186651503-cd6f4b1e-3caa-4558-bd56-8bebda4ab708.png" width=400>

[Gabriel Schama](https://www.gabrielschama.com/2016lasercuts/) - laser cut filagree


## Homework
- [Exercise 1 - Laser Cut Stencil](../exercises/ex1.md)
  - DUE Wednesday 9/4. 
- Create a [Digital Sketchbook](https://canvas.unl.edu/courses/185978/assignments/1807023) and add images/description of this project.
  - DUE Wednesday 9/4. Submit your link on [Canvas](https://canvas.unl.edu/courses/185978/assignments/1807023).

## References
- [Rhino Learn](https://www.rhino3d.com/learn/?keyword=kind:%20rhino_win) video tutorials
- [More Rhino Youtube tutorials](https://www.youtube.com/@TheRhinoEssentials)
