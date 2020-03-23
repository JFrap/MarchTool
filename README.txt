Marchtool is a simple tool to get started with/rapidly prototype 3D ray marching. This program is more of a toy than an actual tool at this stage, but who knows what'll happen to it.

When starting the program for the first time, a shader.fs file will be generated containing some sample code in which you may write your own. The function "SceneSDF" must remain for the program to function. The shader and opengl profile is 3.3 core.

- Its shit.
Yea, I know.

- Linux when?
Haha, no. 

...

In all seriousness, I don't know a thing about linux or how it works but if you really want to port this to linux, either dig through my Marcher repo or, if you want to do your sanity a favour, write your own. My codebase is a mess at the moment.

Helper functions and variables:

Time - float, number of seconds passed since program start.
SetDiffuse(vec3); - sets the surface colour/diffuse.
