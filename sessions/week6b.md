# Week 6b - Intro to 3D Printing

| [Wednesday](#wednesday) |


## Wednesday

- Ultimaker Training at top of class
- Introduction to 3D Printing
  - [Importing Models](#importing-models)
  - [Prepping for 3DP](#prepping-for-3dp)
  - [Slicing for 3DP](#slicing-for-3dp)
- Intro to the 3d Printer
- [Homework](#homework)

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

#### Example
<img width="600" alt="image" src="https://user-images.githubusercontent.com/1598545/191771117-8152421f-1818-4d31-8464-bcbce680bcfb.png">

Rhino file: [../examples/venus_sculpture.3dm](../examples/venus_sculpture.3dm)

### Slicing for 3DP
- Use Cura on the Innovation Studio computers for Ultimaker.
- [Download Prusa Slicer]([https://www.prusa3d.com/drivers/](https://www.prusa3d.com/page/prusaslicer_424/))
  - We have the [Prusa MK3S+](https://help.prusa3d.com/tag/mk3s-2)
- Load your STL file from the previous steps. 
- Check scale, positioning. 
- Select print parameters.
  - Material. Slicing. Support. 
- See the complete First Print with Prusa Slicer article from Prusa: [https://help.prusa3d.com/article/first-print-with-prusaslicer_1753](https://help.prusa3d.com/article/first-print-with-prusaslicer_1753)

## Homework

<img src="https://user-images.githubusercontent.com/1598545/191767959-277d1211-81ab-421a-89c4-466806e0cbb4.png" width=600>

**Venus of Willendorf** (25000bce) [stl file](https://www.myminifactory.com/object/3d-print-venus-of-willendorf-at-the-naturhistorisches-museum-vienna-austria-11455) from Scan the World on myminifactory

### Description
You are going to combine a 3d scanned object with a base and text to make a small trophy (< 3" x 3" x 3"). Try to come up with some interesting combination between text, object, and base.

1. Find a 3d model you want to work with. See references below. It does not have to be a historical artifact.
2. Import your scanned object into Rhino.
3. Create an extruded base
4. Add Text. 
5. Slice this model for the Ultimaker or Prusa MK3S+, PLA filament.
6. Finally you will 3d print this model. 

### Submission
- Add documentation of this (screenshots of rhino, screenshot of the slicer, and photo of your printed object) to your digital sketchbook. 
- Submit a pdf of these pages from the digital sketchbook to [Canvas](https://canvas.unl.edu/courses/185978/assignments/1807033). 
- DUE: Wednesday 10/16/24 at 15:00.


## Office Hours 
Discord or by appointment.

## Reference
- Prusa has great Tutorials.
- First Print with Prusa Slicer [https://help.prusa3d.com/article/first-print-with-prusaslicer_1753](https://help.prusa3d.com/article/first-print-with-prusaslicer_1753)


### Places to get 3d models
- [https://www.printables.com/](https://www.printables.com/)
- [https://www.myminifactory.com/](https://www.myminifactory.com/)
- [https://www.thingiverse.com/](https://www.thingiverse.com/)
- [https://3d.csm.ai/](https://3d.csm.ai/)
- Search for **.STL** files on google. If you find a good source, share it with me.

## Meshmixer
- [Download Meshmixer](https://www.meshmixer.com/download.html)
- Hacking things together with meshmixer.
- Exporting for 3DP (.STL)
