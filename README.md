# HCI-Diploma-Project
This includes the files from the Unity project as well as the arduino sketch and its dependancies. The models were removed from the Unity project to make it possible to upload here.

The arduino sketch must be loaded into the arduino board BEFORE running the Unity project. To calibrate the motion sensor, place the device on a level surface and reset it. Calibration takes place after every reset of the Arduino Board.

Different Unity scenes use different input methods. Some are played with a keyboard (for comparison purposes) and some with the controller prototype.

Scenes included in this implementation include the early demos, the thesis presentation demo as well as a separate demo created to test the efficiency of the tool in gesture-based user authentification.

Note 1: The project requires the controller prototype to run the motion-controlled scenes. The Arduino on its own lacks the motion-sensing capability.

Note 2: Unity's compatibility mode needs to be set from .NET 2.0 subset to .NET 2.0 in order for it to support serial communication with the Arduino.

Note 3: The Unity package for the entire project was too big to upload here.
