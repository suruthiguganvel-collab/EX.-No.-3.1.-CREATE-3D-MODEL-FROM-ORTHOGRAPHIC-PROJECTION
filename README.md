# EX. No.3.1. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:3/11/2026

## AIM:
To create a 3D model from given orthographic projection."
Detailed Explanation: The primary objective of this lab exercise is to convert 2D orthographic engineering drawings—such as the Front View, Top View, and Side View—into a complete, accurate 3D solid model using computer-aided design software.
Through this process, designers learn how to sketch 2D profiles based on structural blueprint and transform them into functional 3D parts using tools like extrusion.

## REQUIREMENTS:
1.Autodesk Fusion 360: The core cloud-based Computer-Aided Design (CAD) software utilized for sketching, 3D modeling, and engineering design.
2.Windows 10: The minimum required operating system environment needed to run the Fusion 360 application smoothly and reliably.
3.16 GB of RAM: High-performance memory capacity required to handle complex 3D graphics and rendering operations (integrated graphics with 1 GB VRAM or more is strongly recommended).
4.Internet Connection: A stable broadband connection with a download speed of 2.5 Mbps or faster, and an upload speed of 500 Kbps or faster to support cloud saving and workspace syncing.

## PROCEDURE:
1.Open new file and then select sketch icon:  
Explanation: First, launch the CAD software (such as Autodesk Fusion 360) and create a brand new design document. Once the workspace is open, you need to click on the "Create Sketch" icon (which usually looks like a pencil drawing on a plane) to enter the 2D sketching environment.  
2. Select the plane for sketching:  
Explanation: Before you can start drawing, the software requires you to choose a 2D reference plane on which your sketch will lie. You can choose from the standard coordinate planes based on your view requirement: the XY plane (Top view), XZ plane (Front view), or YZ plane (Side view).  
3. Use sketching features (line, circle, arc, rectangle, polygon, etc.) to draw the given sketch:  
Explanation: Once…

![image](https://user-images.githubusercontent.com/113594316/198551199-8d9b7f6c-6ea7-4d59-8e8c-173f2b5e088f.png)

4.	After creating basic 2D shapes, you use the Modify panel tools to edit, refine, or adjust your drawing geometry. Instead of redrawing complex shapes from scratch, these modifying features allow you to alter existing lines quickly.  
Here is what the primary modification tools shown in the image menu do:  
1.Trim (Shortcut: T): Removes unwanted, extra, or overlapping line segments up to their nearest intersection point.  
2.Fillet & Chamfer: Rounds sharp corners with a smooth arc (Fillet) or cuts off corners at an angle (Chamfer).  
3.Extend & Break: Extend lengthens a line until it meets another geometry, while Break splits a continuous line or curve into separate segments at an intersection.  
4.Offset (Shortcut: O): Creates a parallel copy of selected lines or profiles at a specified uniform distance.  
5.Move / Copy (Shortcut: M): Relocates, rotates, or creates duplicate instances of selected sketch elements anywhere on the plane.  
6.Sketch Scale: Enlarges or shrinks selected sketch geometry proportionally by a defined scale factor.

![image](https://user-images.githubusercontent.com/113594316/198551220-c7aa6694-4427-48e2-9d91-cd7e9615d651.png)

5.	After modifying your drawing, you use the Inspect panel to verify and check the measurements of your sketch to ensure complete accuracy before creating a 3D model.  
Here is how the Inspect tool works and what it does:
1.Measure Tool (Shortcut: I): Allows you to select any line, curve, or pair of points to check measurements such as length, distance, angle, diameter, or radius.  
2.Verification Without Modification: Unlike driving dimensions, using the Measure tool under the Inspect menu lets you read accurate values without adding new sketch dimensions or altering the existing geometry.  
3.Additional Analysis Tools: The Inspect menu also provides advanced diagnostic tools (like Curvature Map, Section Analysis, or Center of Mass) to evaluate geometry alignment, surface quality, and geometric properties.

![image](https://user-images.githubusercontent.com/113594316/198551270-45875855-43a7-4471-af35-bd10cd9dd153.png)

6.	After finishing the sketch use finish sketch option to finalize the sketch.
 Once you have drawn all your shapes, applied dimensions, and verified the measurements, you need to exit the 2D sketching environment to return to the 3D workspace.  
Here is what clicking Finish Sketch does:
1.Exits 2D Mode: Clicking the green checkmark button labeled FINISH SKETCH exits 2D drawing mode and locks in the parameters of your profile.  
2.Prepares Profile for 3D Operations: It closes the active grid environment and converts your 2D geometry into a finalized profile ready for 3D modeling features like Extrude, Revolve, Sweep, or Loft.  
3.Saves Sketch in Timeline: The finalized sketch gets saved as a distinct feature item in the design tree/timeline, allowing you to double-click and re-edit it anytime later if adjustments are needed.

![image](https://user-images.githubusercontent.com/113594316/198551309-8d7ac6c8-6740-479f-8186-195c89823fda.png)

7.	Use extrude option to convert 3D model from sketch
This step takes your flat 2D profile and transforms it into a solid 3D object by giving it depth and volume.  
Here is how the Extrude tool works and what it does:
1.Converts 2D to 3D (Shortcut: E): The Extrude command adds thickness to a closed 2D sketch by pulling or pushing it along a specified axis to form a 3D solid body.  
2.Selecting Profiles & Distance: You select the closed sketch area you want to expand, then specify the exact distance or height using the input box or by dragging the direction arrow.  
3.Operations (Join, Cut, Intersect, New Body):
New Body / Component: Creates a brand-new 3D shape.  
Join: Adds material to merge with an existing 3D body.
Cut: Removes material by cutting through existing 3D geometry (creates holes or slots).
4.Taper Angle & Direction: You can extrude symmetrically in both directions, set a taper angle (to make tapered or sloped sides), or extend the extrusion up to a selected object or surface.

![image](https://user-images.githubusercontent.com/113594316/198551340-fe1f3b48-df79-44ef-a4ae-ff1cd22503ea.png)

8.After finishing the model convert to drawing sheet per ISO standard.
Once your 3D model is completely designed and extruded, the final step is to generate a professional engineering 2D drawing sheet (blueprint) that adheres to international drafting standards like ISO (International Organization for Standardization).  
Here is how this process works and what it includes:
1.Switching Workspace (Drawing > From Design): Click on the workspace switcher at the top-left (where it says DESIGN) and select DRAWING \rightarrow From Design.  
Selecting ISO Standard & Sheet Size: A pop-up dialog box will appear allowing you to select:
Standard: ISO (uses metric units like millimeters and standard projections).  
Units: millimeters (mm).
Sheet Size: Choose standard paper sizes such as A4, A3, A2, etc.
2.Placing Orthographic Views: Once the drawing layout opens, you place the primary views of your model onto the title block sheet:
Base View (Front View): The primary view of your model.
Projected Views: Generated automatically from the base view to show Top, Side, and Isometric (3D) views.
3.Adding Dimensions & Annotations: Add final engineering details such as overall length, width, height, hole callouts, centerlines, title block info, and tolerances.
4.Exporting/Printing: Export the finished 2D engineering drawing sheet to PDF or DXF format for production, manufacturing, or submission.

![image](https://user-images.githubusercontent.com/113594316/198551370-54509915-ec69-4862-9c17-156d61a83b11.png)

## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198551872-276f8b80-bea8-4d4a-b2e8-bfdcd1e9d3cc.png)

## OUTPUT:
<img width="1007" height="697" alt="image" src="https://github.com/user-attachments/assets/a7f845ce-e772-4440-8c9d-5367cb943953" />
<img width="984" height="586" alt="Screenshot 2026-11-07 181458" src="https://github.com/user-attachments/assets/3063fd8a-0c52-48a6-8793-225c54e7b254" />

## RESULT:
Thus, the 3D solid model was successfully created from the given 2D orthographic projection views using Autodesk Fusion 360, and the corresponding engineering drawing sheet was generated according to ISO standards.
