## Project Overview
This Unity project is built using the Spatial Creator Toolkit. It features a space where an avatar navigates through a path encountering hazardous objects like broken vases. The project explores how auditory cues simulate perception of discomfort in VR environments and their impact on user engagement and embodied interaction.

## Protocol Documentation   
The protocol implementation document is available in the Protocol Documentation in this repository Protocol\Protocol and Implementation.pdf

## Features
3D Models: Imported from Sketchfab.

Sound Effects: Sourced from Pixabay.

Spatial Triggers: Used to play audio cues.

Testing: Can be tested in the Spatial Sandbox.

Publishing: Can be published on Spatial.

## Experiment setup:

### Requirements:
Unity: Version 2021.3.21f1 (LTS) with WebGL Build Support module.  
Spatial Account: Create a free account at Spatial.io.  
Spatial Creator Toolkit: Download from Spatial Creator Toolkit.  

### Setup Steps

**Install Unity:**
Download and install Unity Hub from Unity Hub.
Install Unity 2021.3.21f1 (LTS) with the WebGL Build Support module.

**Download Spatial Starter Template:**
Download the starter template from Spatial Starter Template.
Extract the .zip archive and open the project in Unity Hub.

**Import Assets:**  
_Sketchfab Models_: 
Download and import 3D models from Sketchfab.

"Dusty path in the fields" (https://skfb.ly/6ATxx)  by 3dhdscan is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/)
[Dusty path](https://sketchfab.com/3d-models/dusty-path-in-the-fields-1386c844619e4006a916383158f7ade5 )

"Broken Vase // LOWPOLY" (https://skfb.ly/oFKzE)  by Vlasov Daniil is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/). 
[Broken vase](https://sketchfab.com/3d-models/broken-vase-lowpoly-6e0f182f408143a3be6381ef02cadddf)

_Pixabay Audio:_ 

Download and import sound effects from Pixabay.

[Ambient Sound](https://pixabay.com/sound-effects/birds-chirping-241045/) 
Free for use under the Pixabay Content License

[Vase Crushing sound](https://pixabay.com/sound-effects/glass-shatter-7-95202/)
Free for use under the Pixabay Content License

**Set Up Spatial Creator Toolkit:**  
Follow the installation guide at Spatial Creator Toolkit Installation.  

**Log Into Spatial Account**  
1. In Unity, click on the Spatial SDK tab in the header.    
2. Select Account to open the Spatial Portal window.  
3. Click on Get Login Token, which will redirect you to your browser.  
4. Copy the login token from your browser and return to Unity.  
5. Click on Paste Login Token in the Spatial Portal window to log in.  

**Functionality**  
1. Broken vases are placed on the path where the avatar walks from point A to point B.  
2. Audio cues are trigged to play when the avatar walks through the broken vases.  
3. Ambient sound plays throughout when the avatar is inside the scene.  
4. Assets\Scenes\DirthPathScene-NoAudio.unity for the scene without audio cues.  
5. Assets\Scenes\DirtyPathScene.unity for the scene with audio cues.  

**Running the Project**  
_1. Testing in Spatial Sandbox_  

    a. Open the project in Unity and ensure all assets are correctly imported.  
    b. Click the Test Scene button in the Unity toolbar to upload the scene to the Spatial Sandbox.  
    c. The scene will automatically open in your web browser for testing.  

_2. Publishing on Spatial_  

    a. Click the Publish button in the Unity toolbar to open the Spatial Portal.  
    b. Click Publish to upload the project to Spatial.  
    c. Monitor the publishing status in Spatial Studio.  

## Source Code and Version Control
Source Code: [Github repository] (https://github.com/hiqb269/Group12-AdvancedHCI-project)

Published version:  
[HCIWalkingPath] (https://www.spatial.io/s/HCIWalkingPath-66f77265c49a36d6cb2cf9c9?share=4156219902008613463)  
[HCI WalkingPath_NoCues] (https://www.spatial.io/s/HCI-WalkingPath_NoCues-66fa34a6c49a36d6cb2cfa15?share=8130704535378550778)  

                

**Additional Resources**  
Spatial Creator Toolkit Documentation: [Spatial Docs](https://toolkit.spatial.io/)  
Unity Documentation: [Unity Docs](https://docs.unity.com/)



