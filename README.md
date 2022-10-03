The following documents my senior year hobby project: Creating an Autonomous Tennis Ball Collector

# Ball Tracking
Using OpenCV in Python, the following program identifies the location of tennis balls given camera input. The program is then integrated into an end-to-end system that locates tennis balls on a court and determines/follows a path to collect them without user input. 

An in-depth guide for implementing this tennisball tracking program can be found at [Ball Tracking with OpenCV](https://pyimagesearch.com/2015/09/14/ball-tracking-with-opencv/)

# Tracking Program Demo
![cut-tracking](https://user-images.githubusercontent.com/45131554/193482573-2ee992bf-58a7-4430-ba06-cda0d9de24b1.gif)

# Implementing the Program
The tennis ball tracking program is run on a Raspberry Pi 4B with a PiCamera module, which uses Serial communication to send instuctions to an Arduino Uno. The Arduino controls the voltage output to two DC motors which control the movement/collection of our mechanical tennis ball collector.

![tennis_robot](https://user-images.githubusercontent.com/45131554/193483187-0819e24c-1df1-44dc-b402-8895a1e7af2b.gif)
![cutTesting](https://user-images.githubusercontent.com/45131554/193483387-15fd94fa-89b4-4710-94a8-5ab5d4f77905.gif)



