# Week 4 - Mesh Creation and Stacked Contours

## Agenda
- Announcements:
  - Configure Rhinoceros Zoo (carson center license for Rhino 6.0)
    - (Update: is working on wired connection, still not working on eduroam for me)
- Q&A on Exercise 3. Cutting time.
- Topics
  - Recap from [last week](sessions/week3.md)
    - new: Fabricating 3D Form from 2D Materials with Laser Cutter ([slides](https://docs.google.com/presentation/d/1ARPiH8T5reSiY5ewIX1UlxRUFG-ZnqqxFOQk_W-92V0/edit?usp=sharing))
  - [Mesh Basics in Rhino](#mesh-basics-in-rhino)
  - [Contours and Stacked Construction](#contours-and-stacked-construction)
  - [Bonus: Pepakura and Unfolding](#bonus-pepakura-and-unfolding)
- [Homework](#homework)
- [Office Hours this Week](#office-hours)

## Mesh Basics in Rhino

__Solids vs. Meshes__ 
[solids_meshes.3dm](../assets/day4/solids_meshes.3dm)
- Solids
  - what are they? (collections of surfaces)
  - explode, cap
  - when we export STL we are creating a mesh
- Meshes
  - Create meshes directly

__Importing Meshes__
- Importing - Import
  - [buffalo.stl](../assets/day4/buffalo.stl)
  - Rotate and Scale as necessary to find and position the object.
- Simplification (MeshReduce)
  - [buffalo_reduction.3dm](../assets/day4/buffalo_reduction.3dm)
- Edit - PointsOn, and directly manipulating points on the mesh.
- Closed vs Open Meshes
  - We need closed meshes for 3DP
  - Attempt to patch an open mesh: Mesh -> Repair Tools -> Fill All Holes

## Contours and Stacked Construction
- Building a 3d form directly with stacks of contours
  - tutorial file [stacked_contours_offset.3dm](../assets/day4/stacked_contours_offset.3dm)
  - freeform drawing
  - offset
  - extrude to priview (optional)

- Slicing a 3d mesh or surface object into 2d stacks
  - the [contour](http://docs.mcneel.com/rhino/5/help/en-us/commands/contour.htm) command
  - [contour_command.3dm](../assets/day4/contour_command.3dm)
  - [contour_flatten_shear.3dm](../assets/day4/contour_flatten_shear.3dm)
- Importing and slicing a complex mesh
  - Finding a mesh (thingiverse.com)
  - Importing a mesh into rhino
  - Slicing a mesh with the contour command
  - slicing/design for digital fabrication (material thickness considerations)
    - [buffalo_contours.3dm](../assets/day4/buffalo_contours.3dm)
    - [sliced_pikachu.3dm](../assets/day4/sliced_pikachu.3dm)
  - sliced pikachu

## BONUS: Pepakura and Unfolding
- [Pepakura Designer](https://tamasoft.co.jp/pepakura-en/)
- In Rhino, we can unfold. more on this later.

## Homework
- Exercise 4 DUE Thursday September 23, 9pm
- Concept for project 1. 2 paragraphs on Canvas.

## Office Hours
- Tuesday afternoon 9/21 
- Wednesday afternoon 9/22 (after 1pm)

## Reference
