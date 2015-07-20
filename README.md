# OpenGL---Saturn-Dice
There are two projects: a rotating Saturn and rolling dice. 
I have implemented two kinds of lighting: Gouraud and Phong shading. Pressing L will alternate between the two shadings. I assigned a color, calculated and assign texture coordinates to the vertex. OpenGL uses these texture coordinates to map sample the image and map it onto a face. Since texture mapping deals with the actual pixel color value, I used the fragment shader to implement texture mapping. 
