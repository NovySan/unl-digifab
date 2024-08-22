# Week 4b - 3D Basics and Unrolling Surfaces

[Wednesday](#wednesday)

## Wednesday

- [Drillpress training at top of class](#drillpress-training)
- [Artist of the Day](#artist-of-the-day)
- [Rhino 3D Basics](#rhino-3d-basics)
- [Unrolling Surfaces](#unrolling-surfaces)
- [Homework](#homework-2)

## Drillpress Training
- Be very, very careful
- Please do not put a hole in your hand.

## Artist of the Day

<img src="https://user-images.githubusercontent.com/1598545/189138511-e74e66cf-12dc-4b3c-b372-a6196d3ee79a.png" height=400>

[**Joseph Delappe**](http://www.delappe.net)

- [Cardboard Ghandi](http://www.delappe.net/project/cardboard-gandhi-2008-2009/)
- [Liberty Weeps](http://www.delappe.net/sculptureinstallation/liberty-weeps/)
- [Paper Soldier](http://www.delappe.net/project/paper-soldier/)
- [The Drone Project](http://www.delappe.net/sculptureinstallation/the-drone-project/)

## Robert's Excellent Video Series
- [https://drive.google.com/file/d/1FKsDfFfptjkkDLEj0PtASqYCQ7PpNILT/view?usp=sharing](https://drive.google.com/file/d/1FKsDfFfptjkkDLEj0PtASqYCQ7PpNILT/view?usp=sharing)

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

## Example 3D Basics

<img width="600" alt="image" src="https://user-images.githubusercontent.com/1598545/189884167-b5e94bb4-daca-4e90-a400-5ef851a55a75.png">

Rhino file: [basics_3d.3dm](../examples/unroll.3dm)

## Example Unrolling Surfaces

<img width="600" alt="image" src="https://user-images.githubusercontent.com/1598545/189140440-1254ab04-b1e7-4424-adbb-2de3c9869f86.png">

Rhino file: [unroll.3dm](../examples/unroll.3dm)

<!--
## Homework
**Pepakura Construction**

- Using a combination of 3d primitives and solid editing tools, design a virtual sculpture you want to fabricate. 
- Using Unroll, Explode, and your 2d drawing tools, flatten this object into a series of pieces that can be fashioned from cut paper. 
- No need to actually cut in the laser cutter unless you have time and want to. 

**Submission**

- Upload your complete rhino file. 
- Take 3-4 screenshots of your rhino object, and add them to your digital sketchbook. 
  - Upload a copy of that page from your sketchbook

DUE: 09/25/2023 15:00
-->

## Reference
- Pepakura Designer: [https://tamasoft.co.jp/pepakura-en/](https://tamasoft.co.jp/pepakura-en/)
- [https://www.polyhedra.net/en/](https://www.polyhedra.net/en/)
- [Exact Flat for Rhino](https://www.exactflat.com/exactflat-for-rhino)

