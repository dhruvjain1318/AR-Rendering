### INFO 5340 / CS 5650
### Virtual and Augmented Reality 
# Assignment 1

Read: [Assignment Instructions](https://docs.google.com/document/d/1CYpsJIGUkey1Uv66yluL_4HWVkHrpCqxaTbYRtdna0g/edit?usp=sharing "Detailed Assignment Instructions")

<hr>

### Student Name:

Dhruv Jain

### Student Email:

dj336@cornell.edu

### Solution (Screen Recording):

https://youtu.be/Ts7m5Tlk4SA

### Work Summary:

1. Needed to download and connect Unity to Android Development Tools and Java Development Kit
2. Then needed to add Vuphoria Package
3. Also uploaded target image to vuforia, downloaded and package, and integrated into Unity
4. Next, connected AR Camera with target image to search for my netID with the Cornell Tech Logo
5. The resources load and instantiate commands were used to load the prefab (moved from scene to prefabs under resources), and instantiate an instance in a specific location
6. Then, used the script to get touches from user, and the touches position
7. Used Lerp to move the render to the touches position, at the set Z position calculated as the distance from the camera to the initial rendering location
