---
layout: default
title: 1-Table
nav_order: 3
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---
<img src="images/Blender-logo.png" style="float:right;width:200px;height:200px;" alt="Blender logo"> 

# Interface Intro Activity 

If you and your group have any questions or get stuck as you work through this in-class exercise, please ask the instructor for assistance.  Have fun!

# 1. Opening a new File in Blender:

-Open Blender. A window should pop up that shows “New File” and “Recent Files”.
-On the left under New File, select “General” to open a new file in a general workspace. A “General Workspace” means your Blender application will be set up so you have access to a large variety of different tools rather than specific tools for something such as Animation or VFX. 

# 2. Deleting and Adding Objects:

You will start with a cube in your scene. For the sake of the exercise, we are going to delete the cube and re-add it just so we can go over how to add and delete objects.  

-Right click on the cube and select “Delete” at the bottom of the pop up window. You can also delete by left clicking the square and pressing Delete on your keyboard.
-Go to “Add” At the top left of the viewport (the area in which your cube was) and click on “Mesh”. You will see there are different meshes you can add to your scene, some which are 2D and some are 3D. Feel free to add ones that look interesting and then practice deleting them from your scene. 
-With nothing in your scene, select “Cube” (NOT the “Plane”). Now you have successfully deleted and readded an object back into your scene file. Keep the cube in your scene.

# 3. Saving in Blender:

It is important to save frequently when using Blender. If your application crashes, it is likely you will lose your unsaved work.

-To save, move your cursor to “File” in the top left corner of the application. Select and drag down to “Save As”. Navigate through your files to a desired saving location, name your project and save. 
**Tip: To save your progress while working, you can use the shortcut “CTRL + S”**

# 4. Navigating the Viewport in Blender:

The window that your cube is in is known as the Viewport and can be tricky to learn how to navigate. Here are some keyboard shortcuts to memorize so you can move around your cube. Practice!

-Pan= Shift + Middle Mouse Button + Drag Mouse
-Zoom= Middle Mouse Scroll
-Rotate= Middle Mouse Button + Drag Mouse

If you’ve never worked in a 3D space before, it may be kind of confusing to understand the dimensions. 3D workspaces are measured by 3 dimensions (3D!). Think of it like Height, Width, and Length: Z being height, and Y and X being the width or length. If you look at the top right window of your viewport, you’ll see a red, blue, and green shape with a Z, Y and X in it. This is called the “Gizmo”. It is a visual representation of the angle you are looking at your scene from. When you move your cursor over to it, it should light up and be enclosed in a circle. You can left-click anywhere within and drag rotate the Gizmo to rotate your scene as well. Or you can select a dimension (Z for example) to snap to a profile shot of that dimension also known as an Orthographic View. To escape from the profile orthographic view simply rotate out of it. 

Now you can move around your object! This is important so you can see it properly from all angles during the modelling process..      

Scaling the Cube into a Rectangle: 

First we are going to change the shape of the cube to look like a flat rectangle (this will be the table top). In a 3D software you do this by Scaling the dimensions. 

Left Click on the cube to select it and then pressing the N key to open the properties tab. This should pop up on the right hand side of the viewport beside the Gizmo.. The properties tab is a window which has information on your model such as the current rotation, scale dimensions, and location. 
Under Dimensions, change the scale to be X: 2m, Y: 4M, and Z: .1M. You can also scale with the scale tool on the left hand tool bar using the “scale” option and dragging each square along the 3 coloured dimensions to heighten, widen, or compress your shape. You should end up with a flat rectangle shape. 
Press CTRL + A to open the “Apply” window and press on “Scale” to apply the scale. (Now Blender will understand your rectangle as an unedited object rather than an edited cube.) 
Save your work with CTRL + S

Loop Cutting A Mesh in Edit Mode:

Instead of adding extra shapes to create the legs of the table, we are going to edit the “Mesh” of the rectangle (think of this like the shell of the shape) by cutting the “Faces” of the shape it into smaller pieces and then “Extruding” shapes from the rectangle we just made. This is best practice for 3D models as it keeps things simple and thus easier to edit later on. To do this, you must turn your Object Interaction mode to “Edit Mode”. 

Change your Object Interaction Mode from Object Mode to Edit Mode at the top left corner beneath the “Edit” and “Render” tabs. Left click on Object Mode and a window will pop up. Select Edit Mode. You can also press “Tab” to switch between Object Mode and Edit Mode easier. 

In Edit Mode we begin to edit Points, Vertices, and Faces. A point is where vertices meet, vertices are lines, and faces are enclosed by vertices. We will be editing the faces today. Currently, each side of your rectangle will have ONE face.You will also see on the left hand side of the screen that you have a lot more tools to use. These are used to edit the mesh of the object.

Bring your cursor over to the navigation gizmo in the top right corner and select the blue -Z option so that you are staring at a direct profile of the bottom half of the table top. 

Select the “Loop Cut” box on the left hand tool bar. It should be a cube with a vertical line going up the centre. Make sure your rectangle is selected (it will be orange tinted if it is selected) by pressing “A” on your keyboard. 

Drag your cursor over to the centre line of the rectangle until an either horizontal or vertical yellow line appears. When it does, click and press CTRL + B and drag your mouse outwards vertically towards the edge of the table one way and then click to apply. It should look like Photo A. Repeat with the vertical dimension so each corner of the rectangle has a + shape and so there are 9 faces on the bottom in total when you count. 
Final Product. Each corner has a small square in the corner. 

Extruding Faces:

Now that we have cut the mesh into smaller faces, we are going to Extrude the little squares we made on each corner of the bottom of the rectangle. We will pull them downward to create the table legs.

Hold the middle mouse button and drag to adjust the angle of the table so you can select all 4 squares and also drag downwards. Press 3 to change to “Face mode” where you can select the faces individually. Hold shift and select the four small squares on each corner of the table at the same time. Now press E and drag down. Watch the Transform Z in the properties tab.Try to have your table’s Z transform to be around 32 m. 

Save with CTRL + S

Exporting Your File: 

Now you have made a beginner table in Blender! If you would like to export your model, follow these steps.

Go to “File” at the top left of the window. Click and select “Export”. 
Find your preferred file destination and then rename if wanted. 
Choose an .STL file or a Wavefront .obj file. Note: .stl files are perfectly fine for simple models that have no colour. 


_______________________________________

2. Click **Create new design**. If the TinkerCad tutorial pane is up on the right-hand side, you will need to get out of it before proceeding. Click on the TinkerCad logo at the top to bring you back to your main page. From there you should see the “Create new design” button. 

3. On the right side of the TinkerCad open a drop-down menu by clicking on **Basic Shapes**, and then select the **Design Starters** option, then the **"A" Letter Icon**. This will display a list of 3D letters that you can scroll down through to find the whole alphabet, plus numbers 1 through 9. <img src="images/tinkercad-keychain-03b.png" style="float:right;width:400px" alt="visual example"> 

4. Drag and drop all the individual letters from a name or word you want to use onto the workplane. 

    <button onclick="toggle('gif1')">Show/Hide Animation</button>
    <div id="gif1">
    <img src="images/tinkercad-keychain-04.gif">
    </div>

5. Select all the letters and then click on the **Align Button**.

6. Then click on the black handle on the bottom left of the text to align the text along the bottom.
    ![Image representation of alignment](images/tinkercad-keychain-05.png)

7. Now move the letter closer together so that they overlap a significant amount so that when your keychain is printed it will stay together when some stress is put on it. See my example below:
    ![Image example](images/tinkercad-keychain-06.png)

    <button onclick="toggle('gif2')">Show/Hide Animation</button>
    <div id="gif2">
    <img src="images/tinkercad-keychain-07.gif">
    </div>

8. <img src="images/tinkercad-keychain-08.png" style="float:right;width:200px" alt="Clicking on the white dot and writing in A.B values"> To make the lettering a bit more interesting we are going to raise every other letter by 2mm from the current 4mm.  To start doing this click on the first letter, and then (A) click on the **white dot** near the middle of the letter (which will then turn red). (B) click on the **4.00** and change the number to “6” and then press the enter key, and the first letter will stand higher than all the rest. Raise every second letter so that your name looks something similar to this:
    ![Image example of raised letters](images/tinkercad-keychain-09.png)

    <button onclick="toggle('gif3')">Show/Hide Animation</button>
    <div id="gif3">
    <img src="images/tinkercad-keychain-10.gif">
    </div>

9. <img src="images/tinkercad-keychain-11.png" style="float:right;width:220px;height:220px;" alt="Drop down menu"> Now we’ll group all the letters together by selecting them all, and then clicking on the **Group** button. All the letters will change to the same colour and you can now select all the letters as one object.
    ![Image example after grouping](images/tinkercad-keychain-12.png)

    <button onclick="toggle('gif4')">Show/Hide Animation</button>
    <div id="gif4">
    <img src="images/tinkercad-keychain-13.gif">
    </div>

10. <img src="images/tinkercad-keychain-14.png" style="float:right;width:250px" alt="Group icon"> The last thing we need to do is to add a loop to your text so you can more easily hang your new design on your key ring. Start by clicking on **Text and Numbers** in the right panel, and then select **Basic Shapes**. This will display basic geometric shapes for us again.  Select the orange cylinder and drag and drop it into the workplane.

    <button onclick="toggle('gif5')">Show/Hide Animation</button>
    <div id="gif5">
    <img src="images/tinkercad-keychain-15.gif">
    </div>

11. Once the cylinder is in the workspace we need to resize. Start by selecting the cylinder, and then (A) clicking on **white handle** at the bottom right which will turn it red. (B) Now click on the **20.00** and change it to **10**. (C) Click on the other **20.00** and change it to **10** as well.  (D) Next select the **white dot** at the top of the cylinder (it will turn red), and then (E) change the **20.00** to **6** and press enter.<br>
    ![Cylinder with measurements of A,B,C](images/tinkercad-keychain-16.png)![Cylinder with measurements of D,E](images/tinkercad-keychain-17.png)

    <button onclick="toggle('gif6')">Show/Hide Animation</button>
    <div id="gif6">
    <img src="images/tinkercad-keychain-18.gif">
    </div>

12. <img src="images/tinkercad-keychain-19.png" style="float:right;width:200px;height:250px;" alt="grey stripped cylinder"> Next we need to make a hole in the middle of the cylinder, so we’ll grab a grey striped cylinder and drop it on the workplane.  Now select the bottom right “handle” and change both the width and depth dimensions from **20.00** to **6**.

13. <img src="images/tinkercad-keychain-20.png" style="float:right;width:220px;height:200px;" alt="Group icon">Drag and drop the grey cylinder into the middle of the orange cylinder.  Now select both cylinders and the text and then press the **Group** button on the top toolbar. 

    <button onclick="toggle('gif7')">Show/Hide Animation</button>
    <div id="gif7">
    <img src="images/tinkercad-keychain-21.gif">
    </div>

14. Lastly, click on the **Export** button on the top right of the toolbar, and then select **.STL** and save the file to your hard drive so it’s ready for the next stage of the 3D printing process.
    ![Final product example](images/tinkercad-keychain-22.png)

<script>  

    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

[NEXT STEP: Cellphone Keychain Stand](2-keychain-stand.html){: .btn .btn-blue }
