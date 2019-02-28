## Virtual Reality Practicum 1

## Goal:

The goal of this excercise is to practice some of the concepts learned in class, and creating a simple VR environment. 

## Directions:

1. Download the GitHub repository
2. Open the scene **Practicum1** located inside: *Assets/Practicum/Scenes/*
3. Delete Main Camera
4. Download [SteamVR plugin V1.2.3](https://github.com/ValveSoftware/steamvr_unity_plugin/releases/download/1.2.3/SteamVR.Plugin.unitypackage)
5. Download VRTK [from GitHub](https://github.com/thestonefox/VRTK.git)
6. Add VRTK and Steam VR into your Unity project Assets folder
7. In your scene **Practicum1** setup the VRTK_SDKManager to run with (at least):
	* VR simulator
	* SteamVR 
8. Design an **outdoor enviroment** that includes 2 different spaces that can be visited by the user
Consideration for your environment design are (implement at least 4):
	1. Skybox:
		- Change the color of the current skybox to something of your choice
		- Add a new procedural skybox
	2. Lighting. Add interesting lights to your environment and modify their values.
		- 3 spot lights
		- 3 point lights
	3. If you are using a terrain, populate it with trees or other elements like rocks or grass.
	4. If you are using a plane as floor, add elements to the space, for example simple objects with textures or specific materials to outline the mood of the envrionment.
	5. Add 5 sounds so the experience is richer, and the get louder when the user gets closer to them 
9. Add navigation either by teleporting 
10. Make at least one obbject grabbale (VRTK_Interactable Object)
11. Use at least 2 of the scripts provided in: *Assets/Practicum/Scripts*
12. Save the scene
13. Commit changes to repository, remember to add a useful commit messages. 
14. Push committed changes to github
15. Take 2 screenshots of your environment, and put them inside of the folder:  *Assets/Practicum/Screenshots*
13. Commit changes to repository, add a commit message: "Screenshots added to the repository". 
14. Push committed changes to github
15. You can leave when done.

---
**NOTE:** Feel free to use and modify any of the scripts provided, add new scripts, and assets to the enviornment.