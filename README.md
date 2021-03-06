﻿# WebGLShapesDemo

# Developed by Mohammed Abdullhak, Jose Hernandez:

- Soure code can be found @ https://github.com/m-abdulhak/WebGLShapesDemo 
- Try it @ https://m-abdulhak.github.io/WebGLShapesDemo/

# List of Features:
- Multiple Rendering Modes, can be changed with "Select Shapes To Render", including:
	1. Showing two triangles, one simple and the other tessellated, both in line/wireframe drawing style 
	2. Showing two tessellated and twisted triangles, both in filled-color form 
	3. Showing four other polygons, starting from a square up to an octagon (skipping heptagon: square, pentagon, hexagon, octagon), in line form 
	4. Showing the same as in the previous item, but as tessellated polygons (in line/wireframe drawing style), each polygon being split into a smaller set of triangles (using 5 recursive subdivisions) 
	5. Show the same as the item above, but as filled and twisted polygons, starting from a triangle on the left to an octagon (skipping heptagon: triangle, square, pentagon, hexagon, octagon), in filled-color form
	6. Interactive Mode with an interface to select:
		- Different shapes combinations (any shape can be selected or deselected among: triangle, square, pentagon, hexagon, octagon)
		- Rendering mode (solid, Gasket, Lines, Gasket Lines)
		- Tessellation depth: 0 (disabled) to 5 sub-divisions
		- Rotation Angle: 0 to 1800 degrees
		- Rotation Mode: Normal or Twist (Twist Only Works With Tessellation Enabled (1-5))
