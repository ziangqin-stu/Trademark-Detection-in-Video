# Get to know about this "project"
* Part of a course final project;
* Detect given trademark in given video segment, output the ideal frame index to insert corresponding advertisement video;
* Mainly use pencv:orb matching, created a "Zoom-In" method to make further detection on algorithm's interested area of a frame and improve algorithm accuracy.

# Abot "Zoom-In":
Imagine you are standing on the roof of a tall building, given a digital camera and a picture of the target trademark. Professor Havalda asks you to find out the advertisement of that trademark on the street around the building via the digital camera.

The frist step that I will do is to zoom out and find some area that some what look like the trademark I am asked to find out. Then I will zoom-in to make further observation. incorrect area will be bounded out after several times of zoom-in observation, correct area will be confidently confirmed after zoom-in observations.

In this project, I find only one interesting area in each frame(scenery in camera lens). Further improvement process may add sliding windows mechanism.

I think this method is faster than ML method like clustering.

A good idea to raise accuracy is to measure whether the shape of the detected target is reasonable, some incorrect output of this algorithm is messed up in shape, but good in number of matched points. 

# How to run:
This is a ipython-notebook "project", "Presentation.ipyn" is for presentation of this final project, please check and run. 
