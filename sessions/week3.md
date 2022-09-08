# Week 3 - Laser Cutter to 3D Form
- [Tuesday](#tuesday)
- [Thursday](#thursday)

## Tuesday
- Artist of the Day [Lauren Baker](https://laurenbaker.net/filter/art/Laser-cut-acrylic)
- [Extruding Curves](#extruding-curves)
  - [Extruding Example](#extruding-example)
- Homework: [Stacked Contours](#homework) (DUE Friday)

## Artist of the Day

<img src="https://user-images.githubusercontent.com/1598545/188630308-bb449780-4e4d-4fba-8fbc-407fd9135e82.png" width=400>

Lauren Baker ([https://laurenbaker.net/filter/art/Laser-cut-acrylic](https://laurenbaker.net/filter/art/Laser-cut-acrylic))

## Extruding Curves
- We can **extrude** a 2d curve into 3 dimensions to see what it would look like as a flat object. 
  - [_ExtrudeCrv_](https://docs.mcneel.com/rhino/7/help/en-us/index.htm#commands/extrudecrv.htm) **<--- THIS IS OUR GOTO**
- Load up your tab and slot construction from last week (or make a new one).
- If you have not already, join the perimeters for each of the pieces so that you have continuous outlines. 
- Extrude the curves into three dimensions using Extrude Curve.
- Use the transformations and object snaps to assemble your pieces together into a virtual model: 
  - [_Move_](https://docs.mcneel.com/rhino/7/help/en-us/commands/move.htm)
  - [_Rotate_](https://docs.mcneel.com/rhino/7/help/en-us/commands/rotate.htm)
  - [_object snaps_](https://docs.mcneel.com/rhino/7/help/en-us/user_interface/object_snaps.htm)
- Take a screenshot ([_ViewCapture_](https://docs.mcneel.com/rhino/7/help/en-us/commands/viewcapture.htm#ViewCaptureToFile)) and save to file. 
  - Rotate the viewport to capture a number of different vantage points.
  - Experiment with the [_Display Options_](https://docs.mcneel.com/rhino/7/help/en-us/options/view_displaymode_options.htm) to choose an aesthetically pleasing render.

### Extruding Example
<img width="400" alt="image" src="https://user-images.githubusercontent.com/1598545/189135643-7c5be2f6-b27e-4d34-ac53-f457c74b61b6.png">

Rhino file: [stacked_contours_offset.3dm](../examples_stacked_contours_offset.3dm)

Workflow: 
- draw some curves using the 2d drawing tools (Curve, Line, Trim/Join, etc.)
- [_Offset_](http://docs.mcneel.com/rhino/7/help/en-us/commands/offset.htm)
- [_ExtrudeCrv_](https://docs.mcneel.com/rhino/7/help/en-us/index.htm#commands/extrudecrv.htm)
- Move the curves into position, stacking them vertically.


## Stacking Contours
## Homework
**Stacked Contours**
- Draw a series of contours (curves, lines–line art) which you will then stack into 3 dimensions. 
- Assemble these in 3d. 
- Document your resultant assemblage with a number of screenshots (3 minimum). 
- Upload your Rhino File and screen shots to Canvas: [https://canvas.unl.edu/courses/137404/assignments/1344055](https://canvas.unl.edu/courses/137404/assignments/1344055). DUE end of this week (Friday 11:59pm)

## Thursday
3d Basics and Contour Extraction
- Artist of the Day
- [Rhino 3D Basics](#rhino-3d-basics)
- Unrolling Surfaces
- Cutting Acrylic
  - Material Tests

## Artist of the Day
[TK]

## Rhino 3D Basics
In rhino we can either natively author 3d shapes (create boxes, spheres, pyramids, etc.), or we can extrude/loft/revolve 2D drawings into 3d shapes. These two methods are typical for CAD softwares. There is one additional distinction between meshes, polysurfaces, solids, but we do not need to deal with that now.

1. 3D Viewports
   - When we are drawing in 3d, we are going to want to switch back to the 4-up view (top, front, right, perspective)
   - [4View](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/4view.htm) four views at once
   - [MaxViewport](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/maxviewport.htm) single view
   - The 4-up viewport lets us see things from the sides to draw in 3d.
2. 3D Primitives (Solids)
   - [_Box_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/box.htm)
   - [_Sphere_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/sphere.htm)
   - [_Cylinder_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/cylinder.htm)
   - What are Solids? ([solid](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#seealso/sak_solid.htm))
3. Solids from Curves
   - [_ExtrudeCrv_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/extrudecrv.htm) **<--- THIS IS OUR GOTO**
   - [_Revolve_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/revolve.htm)
   - [_Loft_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/loft.htm)
4. Boolean Operations (math with objects)
   - [_BooleanUnion_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/booleanunion.htm) join two objects together
   - [_BooleanDifference_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/booleandifference.htm) subtract one object from another
   - [_BooleanIntersection_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/booleanintersection.htm) create a new object from intersection of two objects
   - [_BooleanSplit_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/booleansplit.htm) split and make new objects at every intersection
   - Sometimes these operations may fail. Pay attention to error messages.
5. Exporting solids
   - ```STL files describe only the surface geometry of a three dimensional object without any representation of color, texture or other common CAD model attributes.```
   - [Exporting STL files](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#fileio/stereolithography_stl_import_export.htm)
   - We can open 3D files in programs like [Meshmixer](https://www.meshmixer.com/) (for mesh manipulations) and [PrusaSlicer](https://www.prusa3d.com/prusaslicer/) (which slices files for 3d printing)

## Cutting Acrylic

Acrylic is the most common plastic sheet good that we might cut with the laser cutter. 
- We can vector cut, vector engrave, or raster engrave acrylic very successfully.
- When you first get a new sheet of acrylic, determine what thickness it is (calipers): [measuring thickness](week2.html#measuring-thickness)
- Run some material tests to find speed, power, and current settings.

### Material Tests
- When you first work with a new material, you want to determine what settings work best for cutting and engraving. 
- As a starting point, you can begin with [the suggested settings for common materials](week2.html#power-settings).
- Typically you might produce a small shape (square, or text) which you can run multiple times with different settings for the 
- Full Spectrum Laser (who manufactures our laser) has some material test files we can try: [https://fslaser.com/material-test/](https://fslaser.com/material-test/)

### Plastic Suppliers
- [H&H Plastics](https://www.google.com/maps/dir/40.8298688,-96.7012424/h+and+h+plastics+lincoln/@40.8423437,-96.7027104,13z/data=!3m1!4b1!4m9!4m8!1m1!4e1!1m5!1m1!1s0x8796bb88f445b751:0x4b7f5828f156d80b!2m2!1d-96.6333809!2d40.851637)
- Home Depot, Lowes, etc. 
- [Tap Plastics](https://www.tapplastics.com/) (mail order)


## Homework
[TK]

## Reference
