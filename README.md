This project demonstrate how to create a custom shape using SVG 
(Scalable Vector Graphics) for Intern Technical Task for Perpova developers.

The design consist of:
A 600 x 600  Canvas
A white Background
A custom red  curved shape created using SVG path commands.

Step by Step Code Explanation.
<?xml version="1.0" encoding="UTF-8"?>
Define the file as XML (Extensible Markup Language) which a text-based markup language design to store,structure and transport data by using custom user-defined tags.

Use UTF-8 (Unicode Transform Format-8) is the dominant variable-length character encoding for WWW. for universal Support.

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 600 600">

xmlns (XML namespace)- is an attribute used in XML and HTML (specifically SVG/MathML) to define a unique namespace for elements and attributes

viewBox - Create Coordinate space.Like Drawing Board size.
X starts at 0
Y starts at 0
Width = 600
Height = 600

<rect width="600" height="600" fill="white"/>

rect mean Draw a rectangle covering the full canvas.
Width: 600
Height: 600
Fill color: White

<path d="
    M 285 240 
    L 432 185
    A 190 260 35 1 1 265 85
    Z" 
    fill="#d55656"/>

The <path> element creates a custom shape using commands inside the d attribute

M (Move to) 285 240 Moving the cursor to x=285 y=240 as starting point.
L (Line to) 432 185 draws a straight ine from the current position to x=432 y=185
A (Arc) Draw a curved elliptical arc
190 → X radius

260 → Y radius
35 → Rotation angle (degrees)
1 → Large arc flag (draw larger arc)
1 → Sweep direction
265 85 → Ending position
Z (Close Path)Connects the final point back to the starting point 285,240.This closes the shape so it can be filled.

fill="#d55656" Shape of Color.

Command	Meaning
M	Move to a position
L	Draw straight line
A	Draw curved arc
Z	Close the shape