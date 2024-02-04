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
<summary>Details of this function</summary>

### Length
To calculate the distance from the point to the origin.

### Substract
Subtract the radius to get the signed distance to the circle's surface.

### Step
Function to remove all values between 0 and 1. To remove fading effect.
  
</details>

## Rectangle Mask without fade Function
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="Images/RectangleFunctionDemo.png">
  <source media="(prefers-color-scheme: light)" srcset="Images/RectangleFunctionDemo.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="Images/RectangleFunctionDemo.png">
</picture>
