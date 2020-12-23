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

<img src="./imgs/img_3.4_Trim_1.JPG" width="150"/> &rarr; <img src="./imgs/img_3.4_Trim_2.JPG" width="200"/>

Let’s now use the “__Trim__” command. Type “__TR__” and press “__Return__”.

![image](./imgs/img_3.4_Trim_3.JPG)

Now we are in the “__Trim__” command: first, you have to select the trim edges and then press “__Return__”. Select the up-right and the bottom-left circle.

![image](./imgs/img_3.4_Trim_4.JPG)

Press “__Return__”. Select now the object to trim: the up-left circle (remember to select the outer part of the circle).

![image](./imgs/img_3.4_Trim_5.JPG)

When you'll have finished, press “__Esc__” or “__Return__” to quit the command. Repeat the procedure for all the circles (pay attention to the trim edges):

![image](./imgs/img_3.4_Trim_6.JPG)

#### Task 3.5. - Offset
Before using the “__Offset__” command, select the square and erase it:

![image](./imgs/img_3.5_Offset_1.JPG)

Type “__O__” and press “__Return__”.

![image](./imgs/img_3.5_Offset_2.JPG)

You are asked to specify the offset distance: type “__0.1__” (meaning 10 centimetres) and press “__Return__”.

![image](./imgs/img_3.5_Offset_3.JPG)

Now select the objects and draw the offset outwards:

<img src="./imgs/img_3.5_Offset_4.JPG" width="300"/> &rarr; <img src="./imgs/img_3.5_Offset_5.JPG" width="300"/>

Press “__Return__” to quit the command. Repeat the procedure for all the arches.

<img src="./imgs/img_3.5_Offset_6.JPG" width="300"/> &rarr; <img src="./imgs/img_3.5_Offset_7.JPG" width="300"/>
&rarr; <img src="./imgs/img_3.5_Offset_8.JPG" width="250"/>

#### Task 3.6. - Scale
To scale an object, type “__SC__”:

![image](./imgs/img_3.6_Scale_1.JPG)

The command scales the selected object by the ratio you specify. So select all the objects and press “__Return__”:

![image](./imgs/img_3.6_Scale_2.JPG)

Now select the base point (select the centre), specify now the ratio (type “__0.5__”) and press “__Return__”.

<img src="./imgs/img_3.6_Scale_3.JPG" width="300"/> <img src="./imgs/img_3.6_Scale_4.JPG" width="300"/>

The final result is the same drawing with the dimensions halved.

#### Task 3.7. - Fillet
The command “Fillet” draws and arc that connects two objects; this arc is tangent to the objects and has a specified radius. If you do not enter a number for the radius, the two selected lines will extend to join each other. To use the command “Fillet”, type “__F__” and press “__Return__”:

![image](./imgs/img_3.7_Fillet_1.JPG)

Select the objects to connect:

![image](./imgs/img_3.7_Fillet_2.JPG)

Repeat the procedure for all the arches:

![image](./imgs/img_3.7_Fillet_3.JPG)

#### Task 3.8. - Rotate
Before rotating the drawing, copy it aside (using the command “__Copy__”):

![image](./imgs/img_3.8_Rotate_1.JPG)

Type “__RO__”:

![image](./imgs/img_3.8_Rotate_2.JPG)

Select the copied objects and press “__Return__”:

![image](./imgs/img_3.8_Rotate_3.JPG)

Specify the base point (centre), type the angle “__45__” and press “__Return__”.

<img src="./imgs/img_3.8_Rotate_4.JPG" width="250"/> &rarr; <img src="./imgs/img_3.8_Rotate_5.JPG" width="500"/>

#### Task 3.9. - Move
Before moving the drawing, paying attention to the trim edges, use the command “__Trim__” to erase the internal part of the rotated figure:

![image](./imgs/img_3.9_Move_1.JPG)

To move objects, select them and type “__M__”:

![image](./imgs/img_3.9_Move_2.JPG)

Press “__Return__” and select the base point (the centre):

![image](./imgs/img_3.9_Move_3.JPG)

Move the base point to the centre of the original drawing:

![image](./imgs/img_3.9_Move_4.JPG)

![image](./imgs/img_3.9_Move_5.JPG)

Now, paying attention to the trim edges, use the command “Trim” to get to the final drawing:

![image](./imgs/img_3.9_Move_6.JPG)

#### Task 3.10. - Explode
Draw a polyline (type “__PL__”) connecting all the external edges. Use then the command “__Offset__” with an offset distance of 0.05m:

<img src="./imgs/img_3.10_Explode_1.JPG" width="300"/> &rarr; <img src="./imgs/img_3.10_Explode_2.JPG" width="300"/>

Now type “__X__” to use the command “__Explode__”. This command breaks complex objects like blocks and polylines into simple objects like lines and arches.

![image](./imgs/img_3.10_Explode_3.JPG)

Select now the internal octagon and press “__Return__”:

![image](./imgs/img_3.10_Explode_4.JPG)

The polyline is now divided in 8 simple lines.

#### Task 3.11. - Extend
This command extends objects to reach specified objects. Type “__EX__”:

![image](./imgs/img_3.11_Extend_1.JPG)

Select the external octagon and press “__Return__”. Select then all the single lines of the internal octagon and make sure that they reach the external octagon on both sides (click on them twice to extend them on both sides):

<img src="./imgs/img_3.11_Extend_2.JPG" width="300"/> &rarr; <img src="./imgs/img_3.11_Extend_3.JPG" width="300"/>
___________________________________________

### Task 4. - Management tools

#### Task 4.1. - Layers
Layers are used in AutoCAD to organise drawings. From the Layer manager you can create new layers and modify the existing ones. By default, AutoCAD uses the “Layer 0”, which is the one we have drawn on so far. This layer cannot be renamed or deleted. It is good habit not to draw on this layer, so let’s start creating our own layers.

Click on “__Layer Properties__”:

![image](./imgs/img_4.1_Layers_1.JPG)

Click on the “__Create new layer__” icon:

![image](./imgs/img_4.1_Layers_2.JPG)

Name it “__Big_scale__” and select the colour “__red__”:

![image](./imgs/img_4.1_Layers_3.JPG)

Create a new layer, name it “__Small_scale__” and assign the colour “__blue__”, then create the layer “__Annotations__” and assign the colour “__green__”:

![image](./imgs/img_4.1_Layers_4.JPG)

Let's now assign the big scale drawing to the “__Big_scale__” layer. Select all the objects of the big drawing and then right-click of the mouse and click on “__properties__”:

![image](./imgs/img_4.1_Layers_5.JPG)

![image](./imgs/img_4.1_Layers_6.JPG)

Here we can view and modify the properties of the selected objects. Change the layer from “__0__” to “__Big_scale__”:

![image](./imgs/img_4.1_Layers_7.JPG)

All the selected objects lay now on the layer “Big_scale” and so they assume the layer’s properties (they are now red). If we wanted them to lay on the “Big_scale” layer, but of a different colour, we can change the colour from the properties menu. Attention: this will change the colour of the selected objects, it WON’T change the colour of the layer.

Let’s now assign the objects of the small drawing to the “__Small_scale__” layer:

![image](./imgs/img_4.1_Layers_8.JPG)

Change the current layer into “__Annotations__”:

![image](./imgs/img_4.1_Layers_9.JPG)

You can see that we are now on the layer “__Annotations__” and everything that we are going to draw will lie on this layer, while everything that is already drawn remains on its own layer.

#### Task 4.2. - Dimension Style Manager
Let’s set up a new dimension style. From the “__Annotate__” menu, click in the bottom-right corner in the “__Dimensions__” section:

![image](./imgs/img_4.2_DimStyle_1.JPG)

This menu will open:

![image](./imgs/img_4.2_DimStyle_2.JPG)

Click on “__New__” to create a new style:

![image](./imgs/img_4.2_DimStyle_3.JPG)

![image](./imgs/img_4.2_DimStyle_4.JPG)

Name it “__My_style_1__” and click on “__Continue__”:

![image](./imgs/img_4.2_DimStyle_5.JPG)

This menu will open:

![image](./imgs/img_4.2_DimStyle_6.JPG)

The most important section of the menu are “__Lines__”, “__Symbols and Arrows__”, “__Text__” and “__Primary units__”. Here you can edit all the settings as you like. Set the parameters as follows:

![image](./imgs/img_4.2_DimStyle_7.JPG)

![image](./imgs/img_4.2_DimStyle_8.JPG)

![image](./imgs/img_4.2_DimStyle_9.JPG)

![image](./imgs/img_4.2_DimStyle_10.JPG)

Let’s now create another style: “__My_style_2__”, which we will use for the small scale drawing:

![image](./imgs/img_4.2_DimStyle_11.JPG)

Set the parameters as follows:

![image](./imgs/img_4.2_DimStyle_12.JPG)

![image](./imgs/img_4.2_DimStyle_13.JPG)

![image](./imgs/img_4.2_DimStyle_14.JPG)

![image](./imgs/img_4.2_DimStyle_15.JPG)

#### Task 4.3. - Dimensions
Make sure that you are on the layer “__Annotations__”; in the “__Annotate__” menu select the style “__My_style_1__”:

![image](./imgs/img_4.3_Dimensions_1.JPG)

Click on “__Dimension__”:

![image](./imgs/img_4.3_Dimensions_2.JPG)

Click on the first and second point of the dimension you want to annotate:

![image](./imgs/img_4.3_Dimensions_3.JPG)

![image](./imgs/img_4.3_Dimensions_4.JPG)

Then move the mouse to a proper distance and click again to quit the command:

![image](./imgs/img_4.3_Dimensions_5.JPG)

Repeat the procedure for several significant dimensions. Once you set the dimension, you can modify it by clicking on it and moving it.

![image](./imgs/img_4.3_Dimensions_6.JPG)

Select then the other style you have created (__My_style_2__):

![image](./imgs/img_4.3_Dimensions_7.JPG)

Repeat the procedure as before for relevant dimensions:

![image](./imgs/img_4.3_Dimensions_8.JPG)

#### Task 4.4. - Measure
If you want to know the measure of an element, but you are not interested in annotating it, you can use the command “__Measure__”. Click on “__Measure__” in the Home menu:

![image](./imgs/img_4.4_Measure_1.JPG)

Then click on the first and on the second point to know the distance between them:

<img src="./imgs/img_4.4_Measure_2.JPG" width="300"/> &rarr; <img src="./imgs/img_4.4_Measure_3.JPG" width="300"/>

#### Task 4.5. - Block
A “__Block__” is a group of selected lines (or other elements) objectified as one entity. To create block, type “__B__” and press “__Return__”. This menu will appear:

![image](./imgs/img_4.5_Block_1.JPG)

First, name your block. Then click on “__Pick point__”, select the base point of your block.

![image](./imgs/img_4.5_Block_2.JPG)

![image](./imgs/img_4.5_Block_3.JPG)

![image](./imgs/img_4.5_Block_4.JPG)

The coordinates of the selected points will appear. Click then on “__Select objects__”, and select all the objects of the small drawing and press “__Return__”:

![image](./imgs/img_4.5_Block_5.JPG)

![image](./imgs/img_4.5_Block_6.JPG)

At the end click on “__Ok__”:

![image](./imgs/img_4.5_Block_7.JPG)

You can always modify your block by opening the “__Block Editor__”:

![image](./imgs/img_4.5_Block_8.JPG)

![image](./imgs/img_4.5_Block_9.JPG)

![image](./imgs/img_4.5_Block_10.JPG)

To close the Block editor, click again on “__Block editor__”:

![image](./imgs/img_4.5_Block_11.JPG)

To insert your block, click on “__Insert__” in the “__Block__” section of the “__Home__” menu:

![image](./imgs/img_4.5_Block_12.JPG)

![image](./imgs/img_4.5_Block_13.JPG)

![image](./imgs/img_4.5_Block_14.JPG)

You can insert your block any time you want and as many times you want.

#### Task 4.6. - Match properties
Another important command you should know about is the command “Match properties”; it is very useful because it applies the all properties of a selected object to other objects (e.g. layer, colour, line type...). To use it, just type “__MA__” and press “__Return__”:

![image](./imgs/img_4.6_MatchProp_1.JPG)

#### Task 4.7. - Layout
We are now going to pass from the model to the layout space. Before doing that, just erase the block you inserted and move the little drawing a little more far away from the big one:

![image](./imgs/img_4.7_Layout_1.JPG)

Click now on “__Layout1__” in the bottom-left corner of the page:

![image](./imgs/img_4.7_Layout_2.JPG)

Zoom out if necessary and this is how the layout space initially appears:

![image](./imgs/img_4.7_Layout_3.JPG)

You can see that if you zoom in and zoom out, the virtual paper become smaller and bigger and if you try to select object, only one object can be selected: this is your only viewport present at the moment. A viewport is like a window on your model; you can move it and modify its shape:

![image](./imgs/img_4.7_Layout_4.JPG)

You can also copy and paste it, like every other object in the model:

![image](./imgs/img_4.7_Layout_5.JPG)

To modify the view of the window, double click on it: now you have access to the model space through the window; if you zoom in and zoom out, your paper will not move, while what’s inside the window will move instead. From here, you can modify everything that is present in the model, but it is better not do that. If you need to modify something, it is better going back to the model space, modify it and then come back to the layout. My advice is to use the viewports just like windows, so what you should do with them is just “view” through them (in other words: centre your drawing and zoom in or zoom out).

Before starting to create our layout, let’s set up the dimensions of our page. In the bottom-left corner of the page, right-click on “__Layout2__” and delete it. Then, right-click on “__Layout1__” and select “__Page setup manager__”:

![image](./imgs/img_4.7_Layout_6.JPG)

Click on “__Modify__”:

![image](./imgs/img_4.7_Layout_7.JPG)

Set “__Adobe PDF__” as “__Printer/plotter__” and “__A4__” as “__Paper size__”:

![image](./imgs/img_4.7_Layout_8.JPG)

Let’s now reshape our viewports: we want a big one for the big drawing and two small ones, one for the small drawing and the other for a detail of the big drawing. To return to the paper space, double click outside the viewport:

![image](./imgs/img_4.7_Layout_9.JPG)

Centre now the drawings in the viewports:

![image](./imgs/img_4.7_Layout_10.JPG)

Let’s now move the small viewports and align them with the big one:

![image](./imgs/img_4.7_Layout_11.JPG)

We centred the drawing manually and also manually we zoomed in and out; but in technical drawings you need a proper scale. To set that, double click on the viewport and then click on the numbers you can see in the bottom-right part of the page:

![image](./imgs/img_4.7_Layout_12.JPG)

Select then the scale “__1:20__”:

![image](./imgs/img_4.7_Layout_13.JPG)

The drawing automatically fits to that scale (if you zoom in or zoom out you will have to this again). Set the scale “__2:1__” for the small drawing:

![image](./imgs/img_4.7_Layout_14.JPG)

And then the scale “__1:10__” for the other one:

![image](./imgs/img_4.7_Layout_15.JPG)

If you did not move the small drawing far enough from the big one, you will see it in the big viewport. In that case, go back to the model, move it away, and then come back to the layout. Now, you have to centre again the small viewport on the small drawing and re-set the proper scale.

In the bottom-right corner, we have the space for the title block. It is possible to draw on the paper as well as in the model (to write a text, click on “__Multi line text__” in the “__Annotation__” section of the “__Home__” menu):

![image](./imgs/img_4.7_Layout_16.JPG)

Write a text and if you want to modify something (like the height) right-click on it, select “__Properties__” and change whatever you want to change:

![image](./imgs/img_4.7_Layout_17.JPG)

![image](./imgs/img_4.7_Layout_18.JPG)

The result should be like this:

![image](./imgs/img_4.7_Layout_19.JPG)

#### Task 4.8. - Plot
To plot your drawing click on “__Print__” and then “__Plot__” in the main menu:

![image](./imgs/img_4.8_Plot_1.JPG)

This is the plot window:

![image](./imgs/img_4.8_Plot_2.JPG)

Check that “__Adobe PDF__” as “__Printer/plotter__” and “__A4__” as “__Paper size__” are set. Set “__monochrome.ctb__” as “__Plot style table__”. Click “__Ok__” and then name the file and select where to save it.

![image](./imgs/img_4.8_Plot_3.JPG)

You should have now a PDF that looks like this:

![image](./imgs/img_4.8_Plot_4.JPG)

More sophisticated ways to plot are available in AutoCAD; for instance, every colour in AutoCAD corresponds to a precise line-weight, so you can plot according to the standard line-weights or modify them and create your own .ctb file to upload when plotting. All this information (and more) can be found in the Autodesk AutoCAD Help (just press F1 when the program is open).