# EX. No.3.1. CREATE-3D-MODEL-FROM-ORTHOGRAPHIC-PROJECTION
## DATE:3/11/2026

## AIM:
To create a complete three-dimensional mechanical component from the given two-dimensional orthographic projection drawing using Autodesk Fusion 360 software. The main objective of this experiment is to understand the conversion of engineering drawings into 3D models by using various sketching, dimensioning, modifying and solid modelling operations.
The experiment also helps to develop practical knowledge of different geometric construction tools and modelling techniques. The given component is constructed by interpreting its front view, top view and right-side view. The specified dimensions, circular portions, curved surfaces, rectangular sections and extended features are considered while developing the final model.

## REQUIREMENTS:
1.Autodesk Fusion 360: The primary Computer-Aided Design (CAD) software used for 3D modeling and sketching.  
2.Windows 10: The operating system required to run the software smoothly.  
3.16 GB of RAM: Required for smooth system performance (integrated graphics with 1 GB or more is recommended).  
4.Internet Connection: A download speed of 2.5 Mbps or faster, and an upload speed of 500 Kbps or faster.

## PROCEDURE:
1.Open new file and then select sketch icon:  
Explanation: First, launch the CAD software (such as Autodesk Fusion 360) and create a brand new design document. Once the workspace is open, you need to click on the "Create Sketch" icon (which usually looks like a pencil drawing on a plane) to enter the 2D sketching environment.  
2. Select the plane for sketching:  
Explanation: Before you can start drawing, the software requires you to choose a 2D reference plane on which your sketch will lie. You can choose from the standard coordinate planes based on your view requirement: the XY plane (Top view), XZ plane (Front view), or YZ plane (Side view).  
3. Use sketching features (line, circle, arc, rectangle, polygon, etc.) to draw the given sketch:  
Explanation: Once inside the sketch mode on your chosen plane, you use various 2D drawing tools from the toolbar (like Line, Circle, Arc, Rectangle, or Polygon) to map out and construct the exact shape or profile of your engineering drawing.

<img width="581" height="663" alt="Screenshot 2026-11-06 124251" src="https://github.com/user-attachments/assets/63dc3e8e-5000-416e-a018-15e4b8ecda7a" />


4.Use sketch modifying features (cut, trim, mirror, move, etc.,) to edit the sketch.
After creating basic 2D shapes, you use the Modify panel tools to edit, refine, or adjust your drawing geometry. Instead of redrawing complex shapes from scratch, these modifying features allow you to alter existing lines quickly.  
Here is what the primary modification tools shown in the image menu do:  
1.Trim (Shortcut: T): Removes unwanted, extra, or overlapping line segments up to their nearest intersection point.  
2.Fillet & Chamfer: Rounds sharp corners with a smooth arc (Fillet) or cuts off corners at an angle (Chamfer).  
3.Extend & Break: Extend lengthens a line until it meets another geometry, while Break splits a continuous line or curve into separate segments at an intersection.  
4.Offset (Shortcut: O): Creates a parallel copy of selected lines or profiles at a specified uniform distance.  
5.Move / Copy (Shortcut: M): Relocates, rotates, or creates duplicate instances of selected sketch elements anywhere on the plane.  
6.Sketch Scale: Enlarges or shrinks selected sketch geometry proportionally by a defined scale factor.

<img width="610" height="626" alt="Screenshot 2026-11-06 105035" src="https://github.com/user-attachments/assets/c34f4273-d262-4cdb-b1cc-00357650c3da" />
<img width="640" height="782" alt="Screenshot 2026-11-06 105101" src="https://github.com/user-attachments/assets/9e3ca553-5ae6-40fc-9cfa-9b0f170b029c" />


5.	Inspecting and Verifying Sketch Dimensions:
After modifying your drawing, you use the Inspect panel to verify and check the measurements of your sketch to ensure complete accuracy before creating a 3D model.  
Here is how the Inspect tool works and what it does:
1.Measure Tool (Shortcut: I): Allows you to select any line, curve, or pair of points to check measurements such as length, distance, angle, diameter, or radius.  
2.Verification Without Modification: Unlike driving dimensions, using the Measure tool under the Inspect menu lets you read accurate values without adding new sketch dimensions or altering the existing geometry.  
3.Additional Analysis Tools: The Inspect menu also provides advanced diagnostic tools (like Curvature Map, Section Analysis, or Center of Mass) to evaluate geometry alignment, surface quality, and geometric properties.

<img width="638" height="644" alt="Screenshot 2026-11-06 105048" src="https://github.com/user-attachments/assets/49f69c23-9516-48a7-9087-3895e314bde2" />


6.	Finalizing the Sketch:
Once you have drawn all your shapes, applied dimensions, and verified the measurements, you need to exit the 2D sketching environment to return to the 3D workspace.  
Here is what clicking Finish Sketch does:
1.Exits 2D Mode: Clicking the green checkmark button labeled FINISH SKETCH exits 2D drawing mode and locks in the parameters of your profile.  
2.Prepares Profile for 3D Operations: It closes the active grid environment and converts your 2D geometry into a finalized profile ready for 3D modeling features like Extrude, Revolve, Sweep, or Loft.  
3.Saves Sketch in Timeline: The finalized sketch gets saved as a distinct feature item in the design tree/timeline, allowing you to double-click and re-edit it anytime later if adjustments are needed
<img width="653" height="351" alt="Screenshot 2026-11-06 105113" src="https://github.com/user-attachments/assets/33787882-f788-4ae8-b515-109d0ea3fa4b" />


7.	Converting 2D Profile to 3D Model (Extrude):
This step takes your flat 2D profile and transforms it into a solid 3D object by giving it depth and volume.  
Here is how the Extrude tool works and what it does:
1.Converts 2D to 3D (Shortcut: E): The Extrude command adds thickness to a closed 2D sketch by pulling or pushing it along a specified axis to form a 3D solid body.  
2.Selecting Profiles & Distance: You select the closed sketch area you want to expand, then specify the exact distance or height using the input box or by dragging the direction arrow.  
Operations (Join, Cut, Intersect, New Body):
3.New Body / Component: Creates a brand-new 3D shape.  
4.Join: Adds material to merge with an existing 3D body.
5.Cut: Removes material by cutting through existing 3D geometry (creates holes or slots).
6.Taper Angle & Direction: You can extrude symmetrically in both directions, set a taper angle (to make tapered or sloped sides), or extend the extrusion up to a selected object or surface.

<img width="645" height="561" alt="Screenshot 2026-11-06 105132" src="https://github.com/user-attachments/assets/036d1b6b-18d2-488f-933d-f84bf99ad8e1" />


8.Generating Drawing Sheet (ISO Standard):
Once your 3D model is completely designed and extruded, the final step is to generate a professional engineering 2D drawing sheet (blueprint) that adheres to international drafting standards like ISO (International Organization for Standardization).  
Here is how this process works and what it includes:
Switching Workspace (Drawing > From Design): Click on the workspace switcher at the top-left (where it says DESIGN) and select DRAWING \rightarrow From Design.  
Selecting ISO Standard & Sheet Size: A pop-up dialog box will appear allowing you to select:
Standard: ISO (uses metric units like millimeters and standard projections).  
Units: millimeters (mm).
Sheet Size: Choose standard paper sizes such as A4, A3, A2, etc.
Placing Orthographic Views: Once the drawing layout opens, you place the primary views of your model onto the title block sheet:
Base View (Front View): The primary view of your model.
Projected Views: Generated automatically from the base view to show Top, Side, and Isometric (3D) views.
Adding Dimensions & Annotations: Add final engineering details such as overall length, width, height, hole callouts, centerlines, title block info, and tolerances.
Exporting/Printing: Export the finished 2D engineering drawing sheet to PDF or DXF format for production, manufacturing, or submission.
<img width="657" height="755" alt="Screenshot 2026-11-06 105146" src="https://github.com/user-attachments/assets/cef9d838-0600-4d20-af60-b1700385326a" />


## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198551872-276f8b80-bea8-4d4a-b2e8-bfdcd1e9d3cc.png)

## OUTPUT:
<img width="1007" height="697" alt="Screenshot 2026-11-07 183550" src="https://github.com/user-attachments/assets/fcf571ee-7369-4a3e-b2be-bfaf74af553f" />
<img width="984" height="586" alt="Screenshot 2026-11-07 181458" src="https://github.com/user-attachments/assets/aee7bcc7-bee6-4c42-b42c-3bf781397316" />



## RESULT:
Thus, the 3D solid model was successfully created from the given 2D orthographic projection views using Autodesk Fusion 360, and the corresponding engineering drawing sheet was generated according to ISO standards.
