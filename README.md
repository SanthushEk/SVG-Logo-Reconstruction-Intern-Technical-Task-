SVG Custom Shape Project
Project Overview

This project demonstrates how to create a custom shape using Scalable Vector Graphics (SVG). It was completed as an intern technical task for Perpova Developers. The main goal of this project is to show understanding of vector graphics, SVG structure, coordinate systems, and path drawing techniques.

The design consists of a 600 by 600 drawing canvas, a white background, and a custom red curved vector shape created using SVG path commands. The shape was manually designed using path logic rather than using automated tracing tools.

Design Structure

The project includes three main components:

A 600 by 600 canvas which acts as the drawing area

A white background that fills the entire canvas

A custom red curved shape created using SVG path commands

XML Declaration Explanation

The project begins with XML declaration. XML stands for Extensible Markup Language, which is a text-based markup language used to store, structure, and transport data using user-defined tags.

UTF-8 encoding is used because it is the most widely used character encoding on the web. It supports international characters and ensures universal compatibility across different platforms and browsers.

SVG Container Explanation

The SVG container defines the drawing space using XML namespace and viewBox attributes.

The XML namespace attribute ensures that SVG elements and attributes are properly recognized by browsers and rendering engines. This is important when working with scalable vector graphics and mathematical graphics formats.

The viewBox attribute defines the coordinate system of the drawing area. It acts like a virtual drawing board where X coordinates increase from left to right and Y coordinates increase from top to bottom. In this project, the coordinate system starts at zero and extends to 600 units in both width and height.

Background Rectangle

A rectangle element is used to create the background of the canvas. The rectangle covers the full width and height of the drawing area, which is 600 by 600. The fill color of the rectangle is white, which provides a clean background for the main shape design.

Custom Shape Using Path Commands

The main visual element of this project is created using the SVG path element. The path element allows designers to create complex shapes using a series of drawing commands defined inside the d attribute.

The shape begins by moving the drawing cursor to a starting position using the Move To command. Then a straight line is drawn from the starting position to another coordinate using the Line To command. After that, a curved elliptical arc is created using the Arc command. Finally, the shape is closed using the Close Path command so that the shape can be filled with color.

Path Commands Explanation

Move To command is used to move the drawing cursor to a specific coordinate without drawing a line. In this project, it moves the cursor to coordinate position 285, 240, which acts as the starting point.

Line To command is used to draw a straight line from the current position to a new coordinate. In this project, a line is drawn from the starting point to coordinate 432, 185.

Arc - command is used to create a curved elliptical arc. The arc command contains several parameters, including horizontal radius, vertical radius, rotation angle, large arc flag, sweep flag, and ending coordinates.

The horizontal radius is 190 units and controls the width of the curve. The vertical radius is 260 units and controls the height of the curve. The rotation angle is 35 degrees, which tilts the arc. The large arc flag is set to 1, which means the larger arc path is drawn. The sweep flag is also set to 1, which controls the direction of the arc. The arc ends at coordinate 265, 85.
The 
Close Path command is used to connect the last point of the path back to the starting point. This allows the shape to be filled with color properly.

Color Design

The shape is filled using the color code #d55656, which represents a soft red tone. This color was selected to create a visually balanced vector shape on the white background.

SVG Command Summary

M command is used to move to a position without drawing.
L command is used to draw a straight line between two points.
A command is used to draw curved elliptical arcs.
Z command is used to close the shape and complete the drawing path.

Learning Outcomes

This project helped in understanding:

SVG structure and syntax

Vector graphic design principles

Coordinate system usage in computer graphics

Path-based shape creation

Arc and line drawing logic
