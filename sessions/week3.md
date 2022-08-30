# Week 3 - Laser Cutter; 2D Digifab
## Agenda
- Announcements:
  - Lecture recordings (try and try again)
  - Digital Sketchbooks
  - Configure Rhinoceros Zoo (license)
    - (Rhino is available in the computer lab as well)
- Review HW1 and HW2
- Topics
- [Homework](#homework)
- [Office Hours this Week](#office-hours)


# Homework
- [Exercise 3](../exercises/ex3.md) DUE Thursday September 16, 9pm

# Office Hours
- Tuesday (9/14) - 12:30-3:15 - Shop hours
- Wednesday (9/15) - 1-2pm

# Reference

# === LEFTOVERS ===

- [Rhino 3D Basics](#rhino-3d-basics)
- [Measuring Objects](#measuring-objects)

# Measuring Objects
- Recording dimensions (pen and paper)
  - [Engineering Drawing and Sketching (MIT)](https://ocw.mit.edu/courses/mechanical-engineering/2-007-design-and-manufacturing-i-spring-2009/related-resources/drawing_and_sketching/)
  - [dimensioned drawings on paper](http://www.pages.drexel.edu/~rcc34/Files/Teaching/MEM201%20L5-Fa0809-SpDimensions_RC.pdf)
- Taking dimensions
  - Ruler
  - Tape measure
  - Digital Calipers. See [Sparkfun: How To Use Calipers](https://www.youtube.com/watch?v=73YJA5giZfs) (youtube link)
  - 3D Scanner
- Transferring dimensions to a Rhino model
- 
# Rhino 3D Basics
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
   - > STL files describe only the surface geometry of a three dimensional object without any representation of color, texture or other common CAD model attributes.
   - [Exporting STL files](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#fileio/stereolithography_stl_import_export.htm)
   - We can open 3D files in programs like [Meshmixer](https://www.meshmixer.com/) (for mesh manipulations) and [PrusaSlicer](https://www.prusa3d.com/prusaslicer/) (which slices files for 3d printing)
