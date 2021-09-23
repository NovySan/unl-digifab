![image](https://user-images.githubusercontent.com/1598545/134498035-b185efc3-02ab-4530-87c3-0a28f6f60ee5.png)

[The Stanford Bunny](http://graphics.stanford.edu/data/3Dscanrep/) (1994)

# Real World and Back Again

Using 3D Scanner App (or polycam), you are going to digitize a real object. The LIDAR scanning on the ipad is a little low-res, so try to digitize something relatively large. We are then going to import this into Rhino, add base, etc., to prepare it for 3D printing, and then export as an STL file.

# Process
1. Capture a 3d scan of a real object.
   - Process the scan. (HD or Fast)
   - Edit the scan. 
   - Simplify if necessary: `More` -> `Simplify Scan`
   - Export. 
      - Export your file as an OBJ file (zipped) with photo texture. This will produce a JPG, a material file (.MTL), and an object file (.OBJ).
      - You need all three files for the textured object to appear correctly (with photos) in Rhino. 
   - Copy your file to your computer with onedrive, airdrop, or your preferred method.
2. Import your OBJ into Rhino.
   - Your 3d scanned file will likely be **very large** (40MB+). Use `ReduceMesh` in Rhino to simplify the file before working with it.
3. Edit the model, add base, add text, prepare for 3D printing.

# Submission
1. Canvas Submission:
   - Three screenshots of your 3d scans either in the scanning app (`More` -> `Capture Thumbnail`) or in Rhino (turn on "Rendered" mode to show photo textures).
   - Rhino file (.3DM)
   - Images of your exported 3DP design (STL) file.
   - (use the naming convention _ex3_Lastname_1.jpg_ and _ex3_Lastname.svg_ _ex3_Lastname.3dm_ for the files.)

2. Sketchbook Updates:
   - upload images of the scans, Rhino file, and STL. 

DUE 9/23, 9pm (Thursday) to [Canvas](https://canvas.unl.edu/courses/114938/assignments/1086825)

# References
- [Image Objects: An Archeology of Computer Graphics](https://mitpress.mit.edu/books/image-objects) by Jacob Gaboury (2021)
