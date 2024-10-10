## 🔴About
**Chauffeur** is a photorealistic driving simulation game that is being developed in Unreal Engine 5. In the game, players take on the role of a chauffeur, responsible for safely delivering clients to their destinations. Within the game, players begin as newcomers in their respective job roles, gradually advancing by joining various groups to build stronger professional connections and increase their affinity.

I use lumen lighting system and nanite technologies to build the game environment. As for the car physics, i use unreal chaos vehicles plugin to simulate the vehicle physics. The car model that is currently used in the game is Porsche 911 GT3, all of the car specs informations are imported into the game to ensure realistic driving experience.

<br>

## 🔥Development Process
- **Environment** <br>The game environment is made by the newest features from Unreal Engine 5 such as lumen, nanite technologies and world partition.<br>- Lumen is a dynamic global illumination system that can calculate light reflections instantaneously, check more about Lumen here: [Lumen](https://dev.epicgames.com/documentation/en-us/unreal-engine/lumen-global-illumination-and-reflections-in-unreal-engine) <br> Nanite is UE virtualized geometry system, capable of rendering high poly counts objects. Check more about Nanite here: [Nanite](https://dev.epicgames.com/documentation/en-us/unreal-engine/nanite-virtualized-geometry-in-unreal-engine)
- **Splines** <br> Spline is very useful for creating repetitive objects, i mostly use spline to create roads and borders such as walls and road railing. In the game, I use different spline tools to create roads as part of the game’s landscape/terrain, while borders are integrated as static objects. 
![image](https://github.com/Felixwijaya04/Felixwijaya04/blob/main/images/Screenshot%20(538).png)
In Unreal Engine, you can create roads using landscape splines by navigating to Landscape mode (shortcut: SHIFT + 2) > Manage > Splines.<br>
![image](https://github.com/Felixwijaya04/Felixwijaya04/blob/main/images/Screenshot%202024-10-08%20120809.png)
<br>Meanwhile, to create borders using spline, we will need an additional spline tool that can be downloaded here for free: [Download Tool](https://tiedtke.gumroad.com/l/splinetools). After importing, you can open the folder and navigate to Spline_Tools folder and drag the type of spline you need and change the mesh slot in the details menu.
- **Vehicle Assets** <br> The current vehicle assets i was using is downloaded from [Sketchfab](https://sketchfab.com/feed). For this game, i search for high poly assets with poly range between 200k to 700k and no modifier applied so i can group each objects easier. Then, i use blender to group each objects into 5 parts (Body, FL Wheel, FR Wheel, RL Wheel, RR Wheel) after that i use UE Vehicle Rigging Addon to automatically rig the vehicle inside blender. You can download it here for free: [UE Blender Vehicle Rigging Addon](https://continuebreak.gumroad.com/l/uYsaQ)


