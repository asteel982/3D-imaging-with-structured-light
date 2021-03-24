# 3D-imaging-with-structured-light
This is the code to run the system outlined in the paper
There are 3 different sections of code the first of which allows for checking of the allignment of the camera with the projected scene
The second part of the code is for taking the required images of the target scene. In this section the phase maps are generated and then automatically projected onto the target 
scene which is then captured by the camera and 3 sensed images are saved of the 3 phase shift projection patterns on the scene. 
The final part of code is the actual 3D image generating. This section retrieves and unwraps the depth data from these 3 sensed images and then generates a 3D image from this 
depth data.
There is also a folder here including some example sensed images that can be used to see how the code produces these 3D images.
