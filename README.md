[TOC]
## Forty  
The opensource x8/x4 compact cinelifter frame 
![](Images\Previews\0_Main.png)
![](Images\Previews\0_Main_01.png)

### Description
Forty is FPV frame designed to carry compact cinema cameras(YES, FX3! NO, FX6!), ultilizing the truss structure for maximum rigidity within reasonable weight.

Plus a sick 3dprintable super structure(v2) with transparent part and RGB LED, the performance of the machine be boosted by 20% for sure!!!(doge)

**Features are listed below:**
- Support 19x19mm motor mounting
  - ![](Images\Previews\1_MotorMount.png)
- Support up to 9 inch prop
  - ![](Images\Previews\1_PropSize.png)
- Support both x8, x4 or unique x4 configuration
  - ![](Images\Previews\1_MultipleConfigurations.png)
- Using truss structure with 5mx8mm arm and 3mm thick motor mount plate
  - ![](Images\Previews\1_ArmStructure.png)
- 2 version of HD camera mounting options
  - ![](Images\Previews\1_2HDCameraMountOptions.png)
- 2 version of landing gear options
  - ![](Images\Previews\1_2LandingGearOptions.png)
- Transparent printable part for LED lighting
  - ![](Images\Previews\1_TransparentParts.png)
- Vibration absorbing balls for HD camera mounts as well as DJI O3 camera
  - ![](Images\Previews\1_DamperSetup.png)
- Support battery sixe up to 160mmx50mm with x8 configuration, x4 configuration can carry bigger battery
  - ![](Images\Previews\1_BatterySpace.png)
- Support 2 xt60 and 1 xt90 connector for different battery layouts
  - ![](Images\Previews\1_xt60xt90.png)
### Parts List

[Parts List Page](./PartsList.md)

Parts will be list for 2 versions, some parts can be shared across vesions
The main difference between these 2 versions are how HD cameras being mounted.

V1 makes everything simple and is easy for maintenance, camera angle ranges form 0 to 30, but it lacks style.
V2 is more stylized, but the printable part are all  weirdly shaped, making 3d printing them not a easy task, Some printable parts even have to take structure load. But hey, at least it looks good, right?

Due to compact design of the frame, both version don't have a big space for HD camera. So compact cinema cameras are suggested, for bigger camera like FX6 or Red komodo, **they will fit**, but watch out for **Vibration absorbing saturation** and **Prop Striking**

### Assembly Guide
if you have access to CAD programe, please download the following Step file, this will save a lot of explanation
[V1 Assembly setp file](./Parts/FullAssembly/Forty_V1.step)
[V1 Full setp file](./Parts/FullAssembly/Forty_V1_Full.step)
[V2 Assembly setp file](./Parts/FullAssembly/Forty_V2.step)
[V2 Full setp file](./Parts/FullAssembly/Forty_V2_Full.step)

Here I will just list some watch-out points when deal with this frame:

- the BasePlate has a lot 30.5x30.5mm mounting spaces, as well as some 25x25mm and some 20x20mm. so you may want spread out your electronics instead of typical flight stack
  - ![](Images\\Guides\Electroniccompartment_1.png)
  - ![](Images\\Guides\Electroniccompartment_2.png)
- Ceiling for FC and Esc compartment is pretty low, both version only have 26mm maxmium of height to work with.
  - ![](Images\\Guides\Electroniccompartment_3.png)
- If you decided to use XT90 bat for this frame, be aware the power cable will have to go throught the 2 rear arms
  - ![](Images\\Guides\PowerCable.png)
- If you decided to use 9inch prop in x8 configuration, be aware any dangling part may causing a prop strike, Due to 9inch prop on inverted motors are extremly close to both xt60 and xt90 connector.
  - ![](Images\\Guides\CableProStrike.png)
- If you decided to use 9inch prop, x4 configuration is suggested, If you found the Prop in HD Camera FOV, try Invert the frontal 2 motors to make the frontal prop lower, and this may improve flight efficiency a little bit~
  - ![](Images\\Guides\FrontalInvertX4.png)
- The V2 features a closed HD camera mount, When mounting a Camera or adjusting camera angle, you have to unscrew a long M4_80, so that the whole camera supporting structure can be fliped up.
  - ![](Images\\Guides\CameraSupportingStructure_1.png)
  - ![](Images\\Guides\CameraSupportingStructure_2.png)

### Addtional