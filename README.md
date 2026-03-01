Project Demonstration – SVG Custom Shape

This project demonstrates how to create a custom red curved shape using SVG (Scalable Vector Graphics) for an Intern Technical Task for Perpova Developers.

Design Specifications:
- Canvas Size: 600 x 600
- Background Color: White
- Custom Shape: Red curved shape using SVG path commands

Step 1: XML Declaration
<?xml version="1.0" encoding="UTF-8"?>

Explanation:
- Defines the file as XML (Extensible Markup Language).
- XML is a text-based markup language used to structure and transport data.
- UTF-8 is the most widely used character encoding on the web and supports international characters.

Step 2: SVG Container
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 600 600">

Explanation:
- svg is the main container for vector graphics.
- xmlns defines XML namespace for SVG elements.
- viewBox defines coordinate space (0,0 to 600,600) allowing scalable rendering.

Step 3: Background Rectangle
<rect width="600" height="600" fill="white"/>

Explanation:
- Creates a white background covering the entire canvas.

Step 4: Custom Red Curved Shape
<path d="M 285 240 L 432 185 A 190 260 35 1 1 265 85 Z" fill="#d55656"/>

Explanation:
- M = Move to starting point (285,240)
- L = Draw line to (432,185)
- A = Draw arc curve with radii 190 and 260, rotation 35 degrees, large arc flag 1, sweep flag 1, ending at (265,85)
- Z = Close path and fill shape

Path Command Summary:
M = Move to position
L = Draw straight line
A = Draw curved arc
Z = Close shape

