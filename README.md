# Unity 2D Platformer Microgame Build
This repository contains a Windows Powershell script to build the Unity 2D Platformer Microgame. The script:
- Clones the 2D Platformer Microgame repostory.
- Uses the Unity Editor version 2020.3.42f1 to build the project for Android.
- Creates build artifacts and uploads them to Artifactory cloud storage.

NOTE: Total build time is approximately 5 to 7 minutes.

Prerequisites:
- The path to Git must be set in the PATH environment variable
- Powershell version 5.0 or greater
- The Unity Editor version 2020.3.42f1 installed in "C:\Program Files\Unity\Hub\Editor\2020.3.42f1\Editor\Unity.exe"

How To Run :
- From a Windows command prompt
     - Open a command prompt as an Administrator
     - Change directory into the root of where this repository is cloned
     - type "powershell -file build.ps1"
     
- From a Powershell command prompt
     - Open a Powershell window as an Administrator
     - Change directory into the root of where this repository is cloned
     - type "./build.ps1"

