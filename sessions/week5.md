# Week 5 - Intro to 3D Printing

| [Tuesday](#tuesday) | [Thursday](#thursday) |

## Tuesday

- Critique

## Thursday

- Introduction to 3D Printing
  - [Importing Models](#importing-models)
  - [Prepping for 3DP](#prepping-for-3dp)
  - [Slicing for 3DP](#slicing-for-3dp)
- Intro to the 3d Printer

### Importing Models

- Create a new file in Rhino and import a 3d scan 
  - [bunny.ply](../assets/day5/bunny.ply) (3MB)
- Find the bunny and scale to an appropriate size. 
  - Locate (Zoom eXtents), Rotate, Scale
  - Simplify Mesh (MeshReduce) if necessary

### Prepping for 3DP
- Add a base
- Add a label (text objects as solids)
- Is it a closed object? 
  - Mesh -> Repair Tools -> **[Fill All Holes](https://docs.mcneel.com/rhino/7/help/en-us/commands/fillmeshhole.htm#FillMeshHoles)**
- Save as STL
  - File -> Export -> select STL file (Stereolithography). Answer yes to most questions.

### Slicing for 3DP
- [Download Prusa Slicer](https://www.prusa3d.com/drivers/) (DRIVERS & APPS)
  - We have the [Prusa MK3S+](https://help.prusa3d.com/tag/mk3s-2)
- Load your STL file from the previous steps. 
- Check scale, positioning. 
- Select print parameters.
  - Material. Slicing. Support. 
- Add multiple objects to a build.

## Homework
[TK]

## Office Hours 
[TK]

## Reference

## Meshmixer
- [Download Meshmixer](https://www.meshmixer.com/download.html)
- Hacking things together with meshmixer.
- Exporting for 3DP (.STL)
