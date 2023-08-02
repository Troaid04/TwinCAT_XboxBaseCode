# TwinCAT XPlanar Xbox Base Code 

### Repo: [`TwinCAT_XboxBaseCode`](https://github.com/Troaid04/TwinCAT_XboxBaseCode)

Use Xbox controller to easily move XPlanar Tiles Around for Development and Demos

---
## Branch Structure:
- `main`
  - working builds / tagged versions
- `develop`
  - Push completed feature branches, fix bugs
  - must build but not necessarily bug free
- Feature branches: [ `feature/x`,  `feature/y`,  `feature/z`, etc... ]
  - implement any features to merge into Develop branch

  
```
main __________v1_________________v2__v2.1____
develop           \_____________//__/
Feature branches:  \\ \   /   /    /
feature/x           \\_\_/   /    /
feature/y            \__\___/    /
feature/z                \______/
```
---
## Functionality 

#### XboxController
 - Button A - Move to nearesat Rotation Point 
	- Rotation outside of rotation point is +- 10 degrees
	- Rotation on a rotation point is endless 
 - Button X - Lock in X Movement 
 - Button Y - Lock in Y Movement 
 - Button B - Activates Anti Slosh 
 - Bumpers - Change Height of mover 
	- Right bumper rises mover
	- Left bumper lowers mover 
 - Triggers - Handle Rotation of mover
	- Right trigger is clockwise rotation 
	- Left Trigger is counter clockwise rotation
	- Rotation outside of rotation point is +- 10 degrees
	- Rotation on a rotation point is endless  
 - Left Stick - X and Y Movement 
 - Right Stick - Tilt 
 - Start button - Enables mover 
 - Back Button - Reset Mover 


#### Mover
 - Input mover type 
 - Input mover max velocity 


#### Environment
 - Input X tiles 
 - Input y tiles 
