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

<img src="https://user-images.githubusercontent.com/1598545/191767959-277d1211-81ab-421a-89c4-466806e0cbb4.png" width=600>

**Venus of Willendorf** (25000bce) [stl file](https://www.myminifactory.com/object/3d-print-venus-of-willendorf-at-the-naturhistorisches-museum-vienna-austria-11455) from Scan the World on myminifactory

### Description
You are going to combine a 3d scanned object with a base and text to make a small trophy (< 3" x 3" x 3").
1. Find a 3d model you want to work with. See references below. It does not have to be a historical artifact.
2. Import your scanned object into Rhino.
3. Create an extruded base
4. Add Text. 
5. Slice this model for the Prusa MK3S+, PLA filament.
6. Finally you will 3d print this model. 

### Submission
- Add documentation of this (screenshots of rhino, screenshot of the slicer, and photo of your printed object) to your digital sketchbook. 
- Submit a pdf of these pages from the digital sketchbook to [Canvas](https://canvas.unl.edu/courses/137404/assignments/1350190). DUE: Wednesday 9/28, 11:59pm.


## Office Hours 
Wednesday 3-5pm or by appointment.

## Reference

### Places to get 3d models
- [https://www.printables.com/](https://www.printables.com/)
- [https://www.myminifactory.com/](https://www.myminifactory.com/)
- [https://www.thingiverse.com/](https://www.thingiverse.com/)
- Search for **.STL** files on google. If you find a good source, share it with me.

## Meshmixer
- [Download Meshmixer](https://www.meshmixer.com/download.html)
- Hacking things together with meshmixer.
- Exporting for 3DP (.STL)
