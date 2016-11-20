# octet

Octet is a framework for teaching OpenGL and the rudiments of game programming such
as Geometry construction, Shaders, Matrices, Rigid body Physics and Fluid dynamics.

It has a number of examples in the src/examples directory.

To use with visual studio, fork this repository into your own account and then
"Clone Into Desktop" using the GitHub tool and open one of the .sln files in src/examples.

There is a python script for generating your own projects from a template.

From the octet directory run:

packaging\make_example.py my_example

To create your own project in src/examples

Examples should also work with Xcode, although testing is a lot less thorough. If it does not work, send
me a pull request with fixes, please...

Octet is a bit unusual in that it does not use external libraries such as libjpeg or zlib.
These are implemented in source form in the framework so that you can understand the code.
The source of most academic libraries is almost unreadble, so we aim to help your understanding
of coding codecs such as GIF, JPEG, ZIP and so on.


Trump Invaders !


Changes


Deleted the stock invader sprite
Replaced the stock sprite with a Trump GIF
Increase in speed after sucess shot
Number of lives is changed to less then lives left 
Changed the size of the sprite and ship 
Altered the number of columns and rows of the invaders.


Project Review 


I have had run into many troubles trying to make the game as different as possible but there were many errors in the process and so instead i have created a simple alternate game to space invaderers called Trump Invaders !. Minimal changes to the original game due to lack of experience in coding. 
