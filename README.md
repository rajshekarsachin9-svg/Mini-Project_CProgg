# 2D Graphics Editor (C)

## Overview

This project is a simple menu-driven **2D Graphics Editor** developed in C. It allows users to draw basic geometric shapes on a character-based canvas using standard graphics algorithms.

The editor supports:

- Drawing Lines
- Drawing Rectangles
- Drawing Circles
- Drawing Triangles
- Displaying the Canvas
- Exiting the Program

The graphics are displayed using ASCII characters in the console.

---

## Features

### 1. Draw Line
Draws a line between two points using Bresenham's Line Drawing Algorithm.

### 2. Draw Rectangle
Draws a rectangle using four lines based on the coordinates of the top-left and bottom-right corners.

### 3. Draw Circle
Draws a circle using the Midpoint Circle Drawing Algorithm.

### 4. Draw Triangle
Draws a triangle by connecting three user-specified vertices.

### 5. Display Picture
Displays the current state of the drawing canvas.

### 6. Exit
Terminates the application.

---

## Canvas Specifications

| Property | Value |
|-----------|--------|
| Width | 80 |
| Height | 24 |
| Empty Pixel | '_' |
| Drawing Pixel | '*' |

---

## Algorithms Used

### Bresenham's Line Drawing Algorithm
Used for drawing horizontal, vertical, and diagonal lines efficiently using integer arithmetic.

### Midpoint Circle Algorithm
Used to generate circles with symmetry and efficiency.

### Polygon Construction
Triangles and rectangles are formed using multiple line segments.

---

## Compilation

Compile the program using GCC:

```bash
gcc graphics_editor.c -o graphics_editor -lm
