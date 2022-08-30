# Week 2 - Laser Cutter

## Tuesday
- Review [Rhino 2D Basics](#rhino-2d-basics)
- Topics
  - [Intro to Laser Cutter](#intro-to-laser-cutter) (hardware hands-on)
  - [Cutting](#cutting)
  - [Design for Laser Cutter](#design-for-laser-cutter)

### Artist of the Day

<img src="https://images.squarespace-cdn.com/content/v1/56d5c341c6fc0815c1e73ee6/1500147928833-2YFUM1ZPJHUTHDOWKBYL/Crossing+Boundaries+%28Black%29+-+Asia+Society+Shot+6_hr.jpg?format=2500w" width=400>

[Anila Quayyum Agha](http://www.anilaagha.com/crossing-boundaries-black)

## Review

### Rhino 2D Basics
1. Create new file from template. Small objects inches.
2. User interface:
   - Switch between single and quad (four-up) display. 
   - Pan, tilt, zoom in display. 
   - Turning __Grid Snap__ on and off. (To create points that stick to origin, 0.25in, etc.) Try as a text command: Type _Snap_ once to turn it on. Once to turn it off.
3. 2D Primitives
   - [_Line_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/line.htm). 
     - Choose start of line, end of line. 
     - Hold __shift__ key while drawing to make the line orthogonal (Right Angle). [_Ortho_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/ortho.htm)
   - [_Rectangle_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/rectangle.htm)
   - [_Circle_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/circle.htm)
   - [_Polygon_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/polygon.htm)
4. 2D Operations
   - [_Trim_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/trim.htm) uses one object to cut and delete parts of another object.
   - [_Split_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/split.htm) uses one object to cut and split another object.
   - [_Join_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/join.htm) connects objects to form a single object
   - [_Extend_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/extend.htm) lengthens or shortens a curve
5. Organization
   - [Layers](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/layer.htm). [Using layers](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#seealso/sak_layer.htm).
   - [_Group_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/group.htm)
   - [_Ungroup_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/ungroup.htm)
   - [Selecting](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#popup_actions/select_objects.htm). How to Select things with the mouse.
   - Selection Menu
6. Transforms
   - [_Scale_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/scale.htm)
   - [_Rotate_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/rotate.htm)
   - [_Move_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/move.htm)
7. Direct Manipulation
   - Changing objects once you have drawn them. We are dealing with [NURBS](https://wiki.mcneel.com/rhino/nurbs)
   - [_PointsOn_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/pointson.htm)
     - Click and drag to move points. Use transforms (_Move_). 
   - [_PointsOff_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/pointsoff.htm)

## Design for Laser Cutter

__Simple Laser Cutter Design__
1. Create new file from template. Small objects inches.
2. Drawing in 2d; using layers
3. Optional: Extrude your layers to the thickness of your material, to see what this would look like __as cut__. 
   - (f.ex. for 1/8" birch plywood you would extrude it to something like 0.125" thick. you can use your calipers to check these measurements)
5. Exporting to SVG.

## Thursday

__Tab and Slot Construction__
1. How can we build 3d structure with 2d materials? 
2. Tab and slot construction? (also called finger joints)
3. You need to design 2d parts that have holes (slots), and other parts that have tabs, so that when cut from flat materials you can assemble them into 3d forms.
4. Optional: Extrude your designs to the thickness of the material, to make solides. Assemble these solides in Rhino to mock up your 3d form.
5. Reference (Video Tutorials):
   - Finger joint laser cut box: https://www.youtube.com/watch?v=FBSQGHBpBWg
   - Finger joint tutorial in Rhino with boolean operations: https://www.youtube.com/watch?v=AYxUUSWIRW4

__Advanced 3D Forms__
- Living hinge construction
  - Kerf Bending Experiments: https://www.martin-breuer.com/kerf-bending-patterns
  - Lattice Hinge Design Workshop: https://futurearchi.org/t/lattice-hinge-design-workshop-starting-from-an-open-source-grasshopper-design/576
- Slicing / panelling tools (breaking 3d structure down into 2d components that can be assembled)
- Parametric design for kerfs and 3d structures (grasshopper)

# Homework
- [TK]

# References
- For your reference: [Rhino Learn](https://www.rhino3d.com/learn/?keyword=kind:%20rhino_win) (tutorials)
- [Sketchup to Rhino Cheatsheet](https://static1.squarespace.com/static/585ca81337c5816afcb8d981/t/5c7478b715fcc0b3c46366d7/1551136953876/Sketchup-Rhino+Cheat+Sheet.pdf)
- ![image](https://user-images.githubusercontent.com/1598545/131845474-7ce17921-1ce1-4601-b6ef-96ec6d62a6cc.png)
- - RetinaEngrave Software:
  - [quick reference guide](https://info.fslaser.com/hubfs/Public_Documents/RetinaEngrave%20v3.0%20RefGuide.pdf)  
  - [Video Tutorials](https://www.youtube.com/playlist?list=PL_1I1UNQ4oGa0w55C772Y1mC6F4f3ZcG6)
  - [RE3.0 Manual](https://info.fslaser.com/hubfs/Public_Documents/RetinaEngrave%20v3.0%20Manual.pdf)
- FSL Muse References:
  - [Muse 3D Manual](https://f.hubspotusercontent00.net/hubfs/2882208/MUSE_MANUAL.pdf)
  - FSL Muse specifications, safety documentation.
  - Suggested starting power settings for FSL Muse (do tests and adjust these for your project):
![image](https://user-images.githubusercontent.com/1598545/132598192-898d58a6-ba56-40fc-8e95-18374daada8a.png)
