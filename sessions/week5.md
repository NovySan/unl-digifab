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




=== LEFTOVERS ===
# Week 5 - 3D Scanning, Rendering, Mesh for 3DP

## Agenda
- Artist of the Day
  - Tivon Rice [Environment Built for Absence](http://tivonrice.com/absence.html)
- Discussion:
  - Thoughts on NIS membership at this point?
  - Configure Rhinoceros Zoo (carson center license for Rhino 6.0)
    - (Update: is working on wired connection, still not working on eduroam for me)
- Discuss Tab and Slot
- Topics
  - Digitizing Objects
  - 3D Scans in Rhino
  - Rhino for 3DP
  - Bonus: Meshmixer
- [Homework](#homework)
- [Office Hours this Week](#office-hours)

## Digitizing Objects
- Two main techniques: photogrammetry and LIDAR
  - Photogrammetry
  - LIDAR / 3d scanning (with laser)
    - ArTec scanner at NIS.

## 3D Scans into Rhino

__Importing a 3D Scan__
- Create a new file in Rhino and import a 3d scan 
  - [bunny.ply](../assets/day5/bunny.ply) (3MB)
- Find the bunny and scale to an appropriate size. 
  - Locate (Zoom eXtents), Rotate, Scale
  - Simplify Mesh (MeshReduce) if necessary

__Prepping for 3DP__
- Add a base
- Add a label (text objects as solids)
- Is it a closed object? 
  - Mesh -> Repair Tools
- Save as STL.

## Slicing for 3DP
- [Download Prusa Slicer](https://www.prusa3d.com/drivers/) (DRIVERS & APPS)
- Load your STL file from the previous steps. 
- Check scale, positioning. 
- Select print parameters.
  - Material. Slicing. Support. 
- Add multiple objects to a build.

## Meshmixer
- [Download Meshmixer](https://www.meshmixer.com/download.html)
- Hacking things together with meshmixer.
- Exporting for 3DP (.STL)

## Homework
- [Exercise 5](../exercises/ex5.md) DUE Thursday September 30, 9pm
- Concept for Project 1. 2 paragraphs on Canvas.

## Office Hours 
- Wednesday afternoon 9/29 (after 1pm)

## Reference
