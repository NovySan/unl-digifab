# Week 2 - Rhino in Depth, 3D
## Agenda
- Configure Rhinocers Zoo (license)
  - (Rhino is available in the computer lab as well)
- Review Rhino 2D Basics
- Measuring Objects
- Rhino 3D Basics
- Homework

# Rhino 2D Basics
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

# Measuring Objects
- Recording dimensions (pen and paper)
- Taking dimensions
  - Digital Calipers
  - Tape measure
  - 3D Scanner
- Transferring dimensions to a Rhino model

# Rhino 3D
In rhino we can either natively author 3d shapes (create boxes, spheres, pyramids, etc.), or we can extrude/loft/revolve 2D drawings into 3d shapes. These two methods are typical for CAD softwares. There is one additional distinction between meshes, polysurfaces, solids, but we do not need to deal with that now.

1. 3D Primitives (Solids)
   - [_Box_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/box.htm)
   - [_Sphere_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/sphere.htm)
   - [_Cylinder_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/cylinder.htm)
     - Solid? ([solids](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#seealso/sak_solid.htm))
2. Solids from Curves
   - [_ExtrudeCrv_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/extrudecrv.htm) **<--- THIS IS OUR GOTO**
   - [_Revolve_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/revolve.htm)
   - [_Loft_](https://docs.mcneel.com/rhino/6/help/en-us/index.htm#commands/loft.htm)

# Homework
- [Exercise 2](../exercises/ex2.md)

# References
- For your reference: [Rhino Learn](https://www.rhino3d.com/learn/?keyword=kind:%20rhino_win) (tutorials)
