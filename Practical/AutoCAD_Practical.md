### CEG2001 - Design of Sustainable Engineering Systems

# AutoCAD Workshop Practical
___________________________________________

#### Maria Pregnolato: maria.pregnolato@bristol.ac.uk
#### Fulvio Lopane: f.lopane@ucl.ac.uk

___________________________________________

### Introduction
This tutorial will cover all the basic commands present in AutoCAD. First, you will familiarise with the AutoCAD environment, and then a series of drawing commands will be presented, followed by a series of editing commands. Finally, more advanced operations will be applied to the drawing, in order to create a final printable technical drawing.

___________________________________________

### Task 1. - Set up

#### Task 1.1. - Create a new drawing
Select “__New__” from the main menu:

![image](./imgs/img_1.1_NewDwg_1.JPG)

Select the “__acad__” file and click “__Open__”:

![image](./imgs/img_1.1_NewDwg_2.JPG)

#### Task 1.2. - Save
First, save your work and remember to do it quite often; Click on “__Save as__” from the main menu and select “__Drawing__”:

![image](./imgs/img_1.2_Save_1.JPG)

Name the file and choose where to save it:

![image](./imgs/img_1.2_Save_2.JPG)

#### Task 1.3. - Drawing units
Select “__Drawing utilities__” from the main menu and click on “__Units__”:

![image](./imgs/img_1.3_Units_1.JPG)

#### Task 1.4. - Cursors
In the AutoCAD environment your cursor will have different shapes according to different situations:
- not in a command;
- in drawring command;
- in modifying command.

![image](./imgs/img_1.4_Cursors_1.JPG)

#### Task 1.5. - Selection
It is possible to select objects by clicking on them or drawing a window around them.

- Window from right to left: selection of everything that the window crosses.

![image](./imgs/img_1.5_Selection_1.JPG)

- Window from left to right: selection of everything that is completely contained in the window.

![image](./imgs/img_1.5_Selection_2.JPG)

Press “__Alt__” to keep selecting; press “__Esc__” to deselect everything.

#### Task 1.6. - Shortcuts

Most used shortcuts in AutoCAD:
- Ctrl + S: Save the dwg file (qsave)
- Ctrl + Z: Undo the previous action (u)
- Ctrl + Y: Redo the undone action again (redo)
- Ctrl + C: Copy
- Ctrl + V: Paste
- Ctrl + P: Open the plot window (plot)

#### Task 1.7. - Snap and tracking
These settings help you to draw accurately. You can usually find them in the bottom-right part of your screen and you can turn them on and off according to your needs.

![image](./imgs/img_1.7_Snap_Tracking_1.JPG)

- ![alt text](./imgs/img_1.7_Snap_Tracking_2.JPG) Grid Display: displays the grid (you can specify the dimensions of the grid)

- ![alt text](./imgs/img_1.7_Snap_Tracking_3.JPG) Ortho Mode: only vertical and horizontal directions can be drawn

- ![alt text](./imgs/img_1.7_Snap_Tracking_4.JPG) Object Snap: snaps on existing object on the screen

- ![alt text](./imgs/img_1.7_Snap_Tracking_5.JPG) Object Snap Tracking: shows snapping reference lines

- ![alt text](./imgs/img_1.7_Snap_Tracking_5.JPG) Polar Tracking: restricts the cursor to specified angles

___________________________________________

### Task 2. - Draw

#### Task 2.1. - Line
There are two ways to draw: selecting the command with the mouse or typing it.
- Select the command “__Line__” from the “__Draw__” menu:

![image](./imgs/img_2.1_Line_1.JPG)

- Type “__L__” (short command):

![image](./imgs/img_2.1_Line_2.JPG)

Click on a random starting point, choose the horizontal direction and type 10 to draw a horizontal line of 10 meters.

![image](./imgs/img_2.1_Line_3.JPG)

#### Task 2.2. - Polyline
Select the Polyline icon or type “__PL__”.

![image](./imgs/img_2.2_Polyline_1.JPG)

Draw a vertical line of 5m and then “close” the triangle as shown below. At the end press “__Esc__”.

![image](./imgs/img_2.2_Polyline_2.JPG)
![image](./imgs/img_2.2_Polyline_3.JPG)

#### Task 2.3. - Rectangle
Draw a rectangle selecting the icon in the “__Home__” menu or typing “__REC__”.

![image](./imgs/img_2.3_Rectangle_1.JPG)

Choose as a starting point the right angle of the triangle as show below:

![image](./imgs/img_2.3_Rectangle_2.JPG)

Type “__D__”, to choose the dimensions of the rectangle and press “__Return__”.

![image](./imgs/img_2.3_Rectangle_3.JPG)

Enter “__10__” and press “__Return__” in order to have a rectangle with a 10 m base. Enter then a height of 5m.

![image](./imgs/img_2.3_Rectangle_4.JPG)

Move the mouse and choose the position of the 10m x 5m rectangle:

![image](./imgs/img_2.3_Rectangle_5.JPG)

When you find it, left click with the mouse.

#### Task 2.4. - Polygon
Under the “__Rectangle__” icon, select “__Polygon__” and then enter the number of sizes “__6__”:

![image](./imgs/img_2.4_Polygon_1.JPG)
![image](./imgs/img_2.4_Polygon_2.JPG)

Type “__E__” to select the edge and not the centre of the polygon.

![image](./imgs/img_2.4_Polygon_3.JPG)

Select the up-right vertex of the rectangle:

![image](./imgs/img_2.4_Polygon_4.JPG)

Then drag the mouse until the bottom-right vertex of the rectangle:

![image](./imgs/img_2.4_Polygon_5.JPG)

#### Task 2.5. - Circle
Open the Circle menu and select “__2-Point__”:

![image](./imgs/img_2.5_Circle_1.JPG)

Select the left vertex of the triangle:

![image](./imgs/img_2.5_Circle_2.JPG)

Then go to the bottom-left corner of the rectangle, but do not click with the mouse. From that point move the mouse leftward keeping a horizontal trajectory (still do not click with the mouse). You will see a green dashed line following your cursor.

![image](./imgs/img_2.5_Circle_3.JPG)

Move the mouse until you will see also a vertical green dashed line:

![image](./imgs/img_2.5_Circle_4.JPG)

At that point left-click with the mouse.

#### Task 2.6. - Spline
Type the command “__SPLINE__” and start picking the vertexes of the polygons starting from the left vertex of the triangle and proceeding clockwise:

![image](./imgs/img_2.6_Spline_1.JPG)
![image](./imgs/img_2.6_Spline_2.JPG)

When you have selected the last point, press “__Return__”.

#### Task 2.7. - Hatch
Type “__H__” and press “__Return__”. The hatch menu will appear:

![image](./imgs/img_2.7_Hatch_1.JPG)

From the pattern menu, select "__ANSI31__":

![image](./imgs/img_2.7_Hatch_2.JPG)

Then select the areas to fill by clicking inside them.

![image](./imgs/img_2.7_Hatch_3.JPG)

___________________________________________

### Task 3. - Modify

#### Task 3.1. - Erase
There are two ways to modify: type full or short name in command line or select the icon (Home/Modify).

![image](./imgs/img_3.1_Erase_1.JPG)

Select the hatch and the spline and press “__Delete__” from you keyboard to erase them:

![image](./imgs/img_3.1_Erase_2.JPG)

#### Task 3.2. - Mirror
The command “__Mirror__” mirrors objects along a line that you define. (It will ask you whether you want to keep the original object or not after defining the mirror line. type “__y__” for yes or “__n__” for no). Select all the objects drawn so far and then type “__MI__” (which is the short command for “__Mirror__”).

![image](./imgs/img_3.2_Mirror_1.JPG)

Press “__Return__” and select the bottom-left corner of the rectangle:

![image](./imgs/img_3.2_Mirror_2.JPG)

Then select the bottom-right corner of the rectangle.

![image](./imgs/img_3.2_Mirror_3.JPG)

Press “__Return__” in order not to erase the source objects.

Repeat the operation using the right sides of the hexagons as mirror axis:

![image](./imgs/img_3.2_Mirror_4.JPG)

![image](./imgs/img_3.2_Mirror_5.JPG)

Repeat it once again, using as mirror axis the line that joins from the bottom-vertexes of the hexagons:

![image](./imgs/img_3.2_Mirror_6.JPG)

![image](./imgs/img_3.2_Mirror_7.JPG)

![image](./imgs/img_3.2_Mirror_8.JPG)

#### Task 3.3. - Copy
This command copies the selected objects from one place to another. Select all the objects drawn so far, type “__CP__” and press “__Return__”.

![image](./imgs/img_3.3_Copy_1.JPG)

Select the bottom-left vertex of the triangle as a base point and click it:

![image](./imgs/img_3.3_Copy_2.JPG)

You will see a preview of where the copy will be drawn:

![image](./imgs/img_3.3_Copy_3.JPG)

Select the up-right vertex of the triangle of the original drawing as an endpoint and click it:

![image](./imgs/img_3.3_Copy_4.JPG)

You will still be able to copy your object wherever you want. To quit the command press “__Esc__”.

![image](./imgs/img_3.3_Copy_5.JPG)

Let's repeat the operation changing basepoint and end point. Select only the original drawing (don't select the copied part) and type “__CP__”:

![image](./imgs/img_3.3_Copy_6.JPG)

As a base point, select the up-left corner of the triangle of the original drawing and as end point the bottom-right corner of the triangle of the copied drawing:

![image](./imgs/img_3.3_Copy_7.JPG)

![image](./imgs/img_3.3_Copy_8.JPG)

#### Task 3.4. - Trim
Before using the “__Trim__” command, draw a square with sides of 0.5m and draw 4 circles with the 4 vertexes of the square as centres and the dimension of the side of the square as a radius:

<img src="./imgs/img_3.4_Trim_1.JPG" alt="drawing" width="150"/> &rarr; <img src="./imgs/img_3.4_Trim_2.JPG" alt="drawing" width="200"/>

Let’s now use the “__Trim__” command. Type “__TR__” and press “__Return__”.

![image](./imgs/img_3.4_Trim_3.JPG)

Now we are in the “__Trim__” command: first, you have to select the trim edges and then press “__Return__”. Select the up-right and the bottom-left circle.

![image](./imgs/img_3.4_Trim_4.JPG)

Press “__Return__”. Select now the object to trim: the up-left circle (remember to select the outer part of the circle).

![image](./imgs/img_3.4_Trim_5.JPG)

When you'll have finished, press “__Esc__” or “__Return__” to quit the command. Repeat the procedure for all the circles (pay attention to the trim edges):

![image](./imgs/img_3.4_Trim_6.JPG)

#### Task 3.5. - 

#### Task 3.6. - 

#### Task 3.7. - 

#### Task 3.8. - 

#### Task 3.9. - 

#### Task 3.10. - 

#### Task 3.11. - 
___________________________________________

### Task 4. - Managing tools

#### Task 4.1. - 

#### Task 4.2. - 

#### Task 4.3. - 

#### Task 4.4. - 

#### Task 4.5. - 

#### Task 4.6. - 

#### Task 4.7. - 

#### Task 4.8. - 