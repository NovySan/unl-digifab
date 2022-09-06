# Week 3 - Laser Cutter to 3D Form
## Tuesday
- Artist of the Day [Lauren Baker](https://laurenbaker.net/filter/art/Laser-cut-acrylic)
- Cutting Acrylic
  - Material Tests
- Stacked Contours
  - Extrusion

## Artist of the Day

<img src="https://user-images.githubusercontent.com/1598545/188630308-bb449780-4e4d-4fba-8fbc-407fd9135e82.png" width=400>

Lauren Baker ([https://laurenbaker.net/filter/art/Laser-cut-acrylic](https://laurenbaker.net/filter/art/Laser-cut-acrylic))

## Cutting Acrylic

Acrylic is the most common plastic sheet good that we might cut with the laser cutter. 
- We can vector cut, vector engrave, or raster engrave acrylic very successfully.
- Reference for cutting/engraving acrylic, refer to our [laser cutter power settings](week2.md#power-settings).
- As a starting point with a new material, after checking it's safety, we could do some material tests.

### Material Tests

## Stacked Contours

## Extrusion

Extrusion 
See **Solids from Curves** below:
 - [_ExtrudeCrv_](https://docs.mcneel.com/rhino/7/help/en-us/index.htm#commands/extrudecrv.htm) **<--- THIS IS OUR GOTO**


## Homework

## Thursday
- Artist of the Day
- [Rhino 3D Basics](#rhino-3d-basics)
- Assembling in 3D

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

## Homework
[TK]

## Reference
