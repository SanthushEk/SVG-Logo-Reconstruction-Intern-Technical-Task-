🎨 SVG Custom Shape Project
📌 Overview

This project demonstrates how to create a custom vector shape using SVG (Scalable Vector Graphics).
It was developed as an Intern Technical Task for Perpova Developers.

The design includes:

✅ 600 × 600 Canvas

✅ White Background

✅ Custom Red Curved Shape using SVG Path Commands

The project helps demonstrate understanding of SVG structure, coordinate systems, and path drawing techniques.

🖼 SVG Code
🧠 Code Explanation
XML Declaration
<?xml version="1.0" encoding="UTF-8"?>

Defines the file as XML format.

UTF-8 encoding provides universal character support.

SVG Container

Attributes:

xmlns → Defines SVG namespace.

viewBox → Creates drawing coordinate space.

Coordinate system:

X-axis starts at 0

Y-axis starts at 0

Canvas size = 600 × 600

Background Rectangle
<rect width="600" height="600" fill="white"/>

Creates a white background covering the entire canvas.

Custom Path Shape
<path d="
M 285 240 
L 432 185
A 190 260 35 1 1 265 85
Z"
fill="#d55656"/>

The shape is created using path commands inside the d attribute.

🔹 Path Commands Used
Command	Meaning
M	Move to starting position
L	Draw straight line
A	Draw curved arc
Z	Close shape
Path Breakdown

M 285 240 → Move to starting point

L 432 185 → Draw straight line

A 190 260 35 1 1 265 85 → Draw curved arc

Z → Close the shape

🎨 Design Details

Shape Color: #d55656 (Soft Red)

Background Color: White

Canvas Size: 600 × 600

🚀 How to Run
Method 1 — Direct Open

Save file as index.svg.

Double click the file.

Open in any modern browser.

Method 2 — VS Code Live Server

Install Live Server extension.

Right click SVG file.

Click Open with Live Server.

🎯 Learning Outcomes

Understanding SVG structure

Working with coordinate systems

Creating shapes using path commands

Using arcs and lines in vector graphics
