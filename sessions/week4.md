# Week 4 - Mesh Creation and Stacked Contours

[Tuesday](#tuesday) | [Thursday](#thursday)

## Tuesday

- [Artist of the Day](#artist-of-the-day)
- [Working with Meshes](#working-with-meshes)
  - [Mesh Example](#mesh-example)
- [Importing Meshes](#importing-meshes) 
- [Extracting Contours](#extracting-contours)
  - [Example Buffalo Contours](#example-buffalo-contours)
  - [Example Sliced Pikachu](#example-sliced-pikachu)

## Artist of the Day

<img src="https://user-images.githubusercontent.com/1598545/189894549-fe5a944d-3d61-4143-8abd-ad4856d9bbac.png" width=600>

Inmi Lee. [_I will not dance_](https://www.inmilee.com/un.html). 2016.

Also:
- [d  i  s p lace](https://www.inmilee.com/displace.html) 2005
- complete [projects](https://www.inmilee.com/index.html)

## Working With Meshes

__Solids vs. Meshes__ 
- Solids
  - what are they? (collections of surfaces)
  - explode, cap
  - when we export STL we are creating a mesh
- Meshes
  - Create meshes directly

### Mesh Example

<img width="600" alt="image" src="https://user-images.githubusercontent.com/1598545/189800138-80ca4469-d7d3-4f3a-ab88-48cb677463e2.png">

Rhino file: [solids_meshes.3dm](../examples/solids_meshes.3dm)


## Importing Meshes
- Importing - Import
  - STL file - Stereolithography ([wikipedia definition](https://en.wikipedia.org/wiki/STL_(file_format)))
  - [buffalo.stl](../assets/buffalo.stl)
  - **Rotate**, **Scale**, and translate as necessary to find and position the object. Also, [Zoom Extents](http://docs.mcneel.com/rhino/7/help/en-us/commands/zoom.htm#Extents)
- Simplification (MeshReduce)
  - [buffalo_reduction.3dm](../assets/day4/buffalo_reduction.3dm)
- Edit directly - **[PointsOn](http://docs.mcneel.com/rhino/7/help/en-us/commands/pointson.htm)**, and directly manipulating points on the mesh.
- Closed vs Open Meshes
  - We need closed meshes for 3DP. Object properties will tell you if a mesh is an open or closed mesh.
  - Attempt to patch an open mesh: **Mesh** -> **Repair Tools** -> **Fill All Holes**
  - Rhino [Mesh Repair](http://docs.mcneel.com/rhino/7/help/en-us/commands/meshrepair.htm) tools

## Extracting Contours

- Slicing a 3d mesh or surface object into 2d stacks
  - the [contour](http://docs.mcneel.com/rhino/7/help/en-us/commands/contour.htm) command
  - [contour_command.3dm](../assets/day4/contour_command.3dm)
  - [contour_flatten_shear.3dm](../assets/day4/contour_flatten_shear.3dm)
- Importing and slicing a complex mesh
  - Finding a mesh (thingiverse.com)
  - Importing a mesh into rhino
  - Slicing a mesh with the contour command
  - slicing/design for digital fabrication (material thickness considerations)
- Simplifying mesh
  - [ReduceMesh](http://docs.mcneel.com/rhino/7/help/en-us/commands/reducemesh.htm)

### Example Buffalo Contours

<img width="600" alt="image" src="https://user-images.githubusercontent.com/1598545/189891871-067e9994-7137-4afd-b115-b3f5a529326b.png">

Rhino file: [buffalo_contours.3dm](../examples/buffalo_contours.3dm)

### Example Sliced Pikachu

<img width="600" alt="image" src="https://user-images.githubusercontent.com/1598545/189891434-480d9b21-ffcf-4623-ae8a-09f4dcfb078f.png">

Rhino file: [sliced_pikachu.3dm](../examples/sliced_pikachu.3dm)

## Homework
Work on project 1 (due in one week, 9/20)

## Thursday
[TK]

## Homework 2
[TK]

## Reference
[TK]

### Cutting Acrylic

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
