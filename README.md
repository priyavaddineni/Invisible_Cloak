# Invisible_Cloak


First capture the background image which acts as replacement when cloak is put

Next capture video and then convert each frame into HSV.
This is because HSV will be really helpful for color detection when compared to RGB & BGR

Now create a mask for the current frame - using isRange() - it creates a binary image - everthing will be black except specified color
Create an inverse mask 

Noise removal and smooting is optional but preferred.
Then use the masks for background and front frames.

Blend both of them to create the effect.
