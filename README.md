# blender-fractal-shader
This is a shader written in Open Shader Language. 
You can use it in Blender's shader node editor, in a "Script" node. 
The shader visualizes a Julia set on z(i+1) = z(i)^2 + c selected by the inputs z and c.
Inputs: 
1. Real and imaginary components of z
2. Real and imaginary components of c

Output:
The shader gives a greyscale color value that represents the number of iterations it takes for z to diverge.
