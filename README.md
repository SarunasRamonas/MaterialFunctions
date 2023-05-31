# SDF Mask Material Function Library
Unreal Engine has limited mask library for materials. This library is created to enhance mask library & document shader programming foundation.

<b>SDF</b> - a sign distance function. A term to describe a function that takes position in space as input and returns the distance from that position to a given shape. It is called signed because the distance is positive outside the shape, negative inside the shape and exactly zero - boundary of the shape.

## Circle Mask without fade Function
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="Images/CircleFunctionDemo.png">
  <source media="(prefers-color-scheme: light)" srcset="Images/CircleFunctionDemo.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="Images/CircleFunctionDemo.png">
</picture>

<details>
<summary>Details of this function WIP</summary>

### Length
Get pixels distance from origin point
Length function - calculate the distance between any given pixel. This function takes a vector as its input and calculates the magnitude of that vector.
Essencially it calculates the distance between the vector and the origin.
$\sqrt{x^2+y^2}$

### Substract
Subtract radius from distance. The values are positive outside the circle's edge which creates a gradient. Negative values are inside the circle resulting in black

### Step
Generate a step function by comparing two values.
  
if x < edge (or y by UE) returns 0.0, otherwise - 1.0
  
</details>
