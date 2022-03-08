# ComputeShaderTutorialStuff
Just some possibly broken code to share while working through a compute shader tutorial.

This isn't really meant as a good resource or anything, I'm just working through a tutorial on compute shaders and needed a place to share some code that isn't working. Specifically, a texture with transparency is being used on quads to create a custom compute shader-based particle effect, but for some reason my code is failing to properly produce the transparent sprites that are desired.

UPDATE: Okay, it's fixed now. In the frag function of the shader code, I was returning the input color value rather than the updated color value with the texture applied. 

In case you're interested, the tutorial I'm following is taught by Nicholas Lever on Udemy at https://www.udemy.com/course/compute-shaders/ 
