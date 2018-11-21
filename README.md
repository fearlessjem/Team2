# 2101Project
VR Safe Riding Project


# VR Riding
VR-riding is a virtual reality (VR) software application that allows cyclists and personal mobility device (PMD) users to practice safe riding on Singapore roads, walkways and shared paths. VR-riding also allows the users to have a free range of motion within the area and give them the feelings of immersion within the virtual environment, thus providing a pleasant and intuitive experience. Ultimately, the aim of VR-riding is to educate users on the safety aspect of commuting by cycling or with their PMD’s in Singapore. 
 
## Setup 

### Project URL
* [Project Link: Google Drive](https://drive.google.com/open?id=1HVzAYGdR2tUlPMDpsFwt39b-0ySC7_s4)

### Dependencies

* [*GoogleVR*](https://github.com/googlevr/gvr-unity-sdk) - For character control, event control & trigger
* [*Android API level 19 and Above*](https://developer.android.com/studio/) - Android SDK

### Installation
#### Windows
1. Download Unity Hub and run 
2. Install Unity3D from Unity Hub
3. Run Unity Hub > Open > Located and select “VRsafeRiding” folder
4. Click on "Play" button in Unity3D

#### Android
1. Install VRsafeRiding_1.0.apk file 

## User Manual
### Admin Manual
*   Select "SCTF Admin" option
	* To view player analytics 
       1. select "View Analytics"
	* To set game setting 
      1. select "Game Setting"
      2. select "Game Level" (1 - 5)
      3. select desired number of vehicles,pedestrian, traffic lights and environment
  
### Player Manual
1. Select "Player" option
2. Select "Level" option
3. Select "Vehicle" option
4. Select "Play" option

### Development Manual
1. All the elements displayed (included vehicle, buildings, pedestrian and etc) in the game are located in the “VRsafeRiding ” > “Assets” folder
2. All the backend c# scripts are located in the “VRsafeRiding ” > “Assets” > “Scripts” folder

### Game Rules
 1. Answer all 8 quiz questions in the game, they are located all over the map
 2. Avoid hitting pedestrians as well as hitting by vehicle and pedestrian 
    in the game
 3. Each question act as a checkpoint(save game progress) in the game 
 4. To restart the game, click on the restart menu located the start of the map .

## Demo
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/tC1cVljr4Yc/0.jpg)](https://www.youtube.com/watch?v=tC1cVljr4Yc)  
*Youtube Link: https://youtu.be/tC1cVljr4Yc*

## Contributors

* *Cao Chenxing - Quiz logic *
* *Han Yu Fong Joseph - Scene Change logic *
* *Jeremy Tan Teng Tat - Game Menu Logic *
* *Lim Jia Hui Alissa - Save User State logic *
* *Lim Yoong Jin - Night Mode Logic *
* *Ng ZhiYuan - Traffic Light Login *


## Errors and bugs
   1. If player is riding with the phone tilted up, he may ride out of the map
   2. Player is not facing the quiz question when he change scene
   3. Traffic lights are being switch on/off at random order
   4. Player's screen camera and his bicyle is able tilt up/down 90 degree at the same time
   5. Vehicles and pedestrian are travel forward and backward without turning its direction
   6. Pedestrian is able to push player away whenever they hit each other.
   7. There is a "delay" time when change between scenes.
   8. When user has changed to quiz scene, the game scene is not on pause state.
   
   
## Limitation
   1. There is no traffic rule implemented in the game
   2. VR-riding currently only supports android mobile
   3. Player's Phone has to be in left screen orientation 

## Feedbacks
   1. Implement a score system to allow player knows his statistics
   2. Implement a Health Point system 
      * Player lose a portion of his health whenever he hitted by vehicle and eventually lose the game if his health runs out
   3. Implement Play-Time Limit system
      * If player unable to finish the game with time limit give, he loses the game

## Copyright and attribution

Copyright (c) 2018 2101Team2Made. Released under the [MIT License](https://github.com/lewisccx/Team2/blob/master/LICENSE.MD).
