Solved 2x2x2 Rubix Cube Using Ortega Method (http://www.cubewhiz.com/ortega.php).

The 3D rendering system was not orignally written by me, it is an adptation on davidwhogg's code from this MagicCube project (https://github.com/davidwhogg/MagicCube).

Feel free to change any of the "Varaible Constants" at the top of the Code (they are self explanatory).

You can scramble and solve the cube using the buttons in the GUI or use press "A" to Scramle and "S" to Solve. 
Both the scramble and solve are printed in the WCA notation (http://meep.cubing.net/wcanotation.html). 
You can manually scramble and solve using the "U D R L F B" keys for each face. Pressing Shift Reverses Rotation Direction. 
Press "T" to run a test that will return the average solve time along with the average number of rotations per solve. 

You can rotate the cude using your left mouse click and zoom using the right mouse click or use the arrow keys. 
Don't try and rotate the cube while the webcam is launched is it crashes the program.  

To launch the webcam press "W" (You may need to change the "CameraNumber" (Line 21)).
To Close the webcam at any time press "Q"

While in the webcam window press "Enter" once to initialize the color recognition function.
By default the program is in "DemoMode" which reads images for those that do not have their own 2x2. 
Show each face to the webcam in turn and press "Enter" when the cube is centered and all the stickers have been correctly detected. (The recognition isn't perfect and I intend to add an editor to amend errors after this process). 
Press "Enter" an 8th time to end the color recognition process. 
You can now solve the that was generated by the webcam and the solve will be printed.
You can also solve your own cube using the generated solve or solve along by following the on screen animation.
To calibrate the color recognition complete the same process but pressing "Space" instead of "Enter".
This will print HSV values that you can replace the values on line 1161. (I understand this is sloppy but I'll add a read and write function for the values. 









