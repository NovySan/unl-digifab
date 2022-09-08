# Week 4 - Mesh Creation and Stacked Contours

- Importing 3d Models
- Working with Meshes
- Extracting Contours

== SOMETIME ==


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


== LEFTOVERS ==

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

========

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
- [solids_meshes.3dm](../assets/day4/solids_meshes.3dm)
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

## BONUS: Pepakura and Unfolding
- [Pepakura Designer](https://tamasoft.co.jp/pepakura-en/)
- In Rhino, we can unfold. more on this later.

## Homework
- ~Exercise 4 DUE Thursday September 23, 9pm~ NO EXERCISE THIS WEEK

## Office Hours
- Tuesday afternoon 9/21 
- Wednesday afternoon 9/22 (after 1pm)

## Reference
