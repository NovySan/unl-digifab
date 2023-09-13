# Week 4b - Wednesday - Mesh Creation and Contour Extraction

| [Wednesday](#wednesday) |

## Wednesday

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

## Robert's Excellent Video Series
- [https://drive.google.com/file/d/1pMrvKhi0zbia2AFm2jC1IMdcXEHAfkUI/view?usp=sharing](https://drive.google.com/file/d/1pMrvKhi0zbia2AFm2jC1IMdcXEHAfkUI/view?usp=sharing)


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
- Go from mesh to unrollable surface: 
  - [MeshToNURB](http://docs.mcneel.com/rhino/7/help/en-us/commands/meshtonurb.htm)

### Example Buffalo Contours

<img width="600" alt="image" src="https://user-images.githubusercontent.com/1598545/189891871-067e9994-7137-4afd-b115-b3f5a529326b.png">

Rhino file: [buffalo_contours.3dm](../examples/buffalo_contours.3dm)

### Example Sliced Pikachu

<img width="600" alt="image" src="https://user-images.githubusercontent.com/1598545/189891434-480d9b21-ffcf-4623-ae8a-09f4dcfb078f.png">

Rhino file: [sliced_pikachu.3dm](../examples/sliced_pikachu.3dm)

## Homework
Work on Project 1 (Due Wednesday 9/27)