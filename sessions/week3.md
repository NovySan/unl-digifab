# Week 2 - Rhino in Depth, 3D
## Agenda
- Configure Rhinoceros Zoo (license)
  - (Rhino is available in the computer lab as well)
- Discuss office hours.
- Introduce Sketchbook.
- Review [Rhino 2D Basics](#rhino-2d-basics)
- [Measuring Objects](#measuring-objects)
- [Rhino 3D Basics](#rhino-3d-basics)
- [Homework](#homework)

# Digital Sketchbook

We will keep a digital sketchbook this semester. This is where I will expect you to include documentation of each exercise, including sketches, snapshots of 3d models, documentation of process. Make a copy of this google doc, and send me a link. [Sketchbook Template](https://docs.google.com/presentation/d/14gCgXjVflWg9KGGCd5hRiVPQyNssw4_FrmWhuZzIRJQ/edit?usp=sharing) 

# Rhino 2D Basics
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

# Homework
- [Exercise 2](../exercises/ex2.md)

# References
- For your reference: [Rhino Learn](https://www.rhino3d.com/learn/?keyword=kind:%20rhino_win) (tutorials)
- [Sketchup to Rhino Cheatsheet](https://static1.squarespace.com/static/585ca81337c5816afcb8d981/t/5c7478b715fcc0b3c46366d7/1551136953876/Sketchup-Rhino+Cheat+Sheet.pdf)
- ![image](https://user-images.githubusercontent.com/1598545/131845474-7ce17921-1ce1-4601-b6ef-96ec6d62a6cc.png)
