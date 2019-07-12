# UE4_VR_Development_101
 Getting started VR development with Unreal Engine 4 
 <br/>
 <br/> 

PREREQUISITES <br/>
Unreal Engine from Epic Game (using 4.21.2 in this demo) <br/>
Any 3D modeling software (Blender/Maya) <br/>
Three button mouse!! <br/>
Hardware (using PC & Oculus Go in this demo) <br/>
 <br/>
 <br/> 

 CONTENT <br/>
 - Preparing 3d model (Sketchfab, Maya/Blender) <br/>
 - Import/Migrate Assets to UE4 <br/>
 - Simple Texture & Material <br/>
 - Blueprint Interaction (Example: moving object) <br/>
 - Deploy to Oculus Go <br/>
 <br/>
 <br/> 

 SETTING UP THE ENVIRONMMENT TO DEPLOY <br/>
 (PC, Phone, Oculus Go) <br/>
1. Go to Folder: Epic Games -> UE_(your engine version) -> Engine -> Extras -> AndroidWorks -> Win64, Run CodeWorksforAndroid Installer to install all of the prerequisites. <br/>

2. Install Oculus Go App on your phone and enable Developer Mode on Developer Settings. <br/>

3. Connect Oculus Go to PC by USB cable. <br/>

4. Open Terminal and type: adb devices. If it is not recoginzed, go to Oculus Go and allow USB debugging. Then, type adb device on Terminal again.<br/>
<br/>
<br/>

DEPLOY TO OCULUS GO WITH UE4 <br/>
<br/>
Project Setting: <br/>
- Description: Project Name, Start in VR <br/>
- Maps & Modes: Default Map <br/>
- Input: Default Touch Interface (clear) <br/>
- Rendering: 2x MSAA, Forward Shading, Instanced Stereo  <br/>
- Android: Accept SDK License, Enable Gradle instead of Ant (disable), Package Name, Minimum SDK Version (21), Target SDK Version (21), Enable FullScreen Immersive on KitKat and above devices, OpenGL ES2 (disable), OpenGL ES3.1 (enable), Configure the AndroidManifest for deployment to GearVR  <br/> 
<br/>
Restart your project and on the Launch dropdown, deploy to your linked Oculus Go device. <br/>





