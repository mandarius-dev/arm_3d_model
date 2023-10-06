# Industrial manipulator - 3D Model of the arm
## Foreword
This is a repository that is a part of five that are meant to help in designing a six-degree-of-freedom manipulator.
Repositories:
 1. Source Code Package [[Link][control]]
 2. 3D Model Spawner Package [[Link][spawner]]
 3. MatLab Scripts [[Link][script]]
 4. **Model of the arm** 
 5. User Interface in LabView [[Link][UI]]

## Content 
This repository contains all the `blender` files along with the `std` files of the whole manipulator.
<img src="https://github.com/mandarius-dev/arm_3d_model/blob/main/media/full_assembly.png" width="450" >

If the models are 3D printed there will be a need to sand down some of the pieces. 

All of the 3D models were designed in Blender and with the help of the `3D-Print Toolbox` all of them are ready for printing. Each link components are in its corresponding folder. Common parts are placed in the `common_pieces` folder. 

## Assembly instruction
Below is some visual instruction on how to assemble the manipulator. Some scrows are necessary to attach some of the pieces together. It is highly recommended to look around the pieces and at the visual instructions in order to have a smooth assembly.

### Link 1
<img src="https://github.com/mandarius-dev/arm_3d_model/blob/main/media/link1.gif" width="400" >

### Link 2
<img src="https://github.com/mandarius-dev/arm_3d_model/blob/main/media/link2.gif" width="400" >
The motor support has been designed to hold a 60 kg servomotor.

### Link 3
<img src="https://github.com/mandarius-dev/arm_3d_model/blob/main/media/link3.gif" width="400" >
The rectangular holes in the pieces are used to hold the servomotors.

### Link 4
<img src="https://github.com/mandarius-dev/arm_3d_model/blob/main/media/link4.gif" width="400" >

### Links 5 and 6
<img src="https://github.com/mandarius-dev/arm_3d_model/blob/main/media/link_5_6.gif" width="400" >

### Full assembly
<img src="https://github.com/mandarius-dev/arm_3d_model/blob/main/media/full_assembly.gif" width="400" >

#### Other models used:   
[Gripper][grp]

[Plastic brings model][bering]

[GT2 gears][gear]

[Raspberry plate][case]


[grp]: https://cults3d.com/en/3d-model/gadget/servo-gripper-for-robotic-arm-sg90-servo-gripper
[gear]: https://www.thingiverse.com/thing:2838757/files
[bering]: https://www.thingiverse.com/thing:2349065
[case]: https://www.thingiverse.com/thing:423216

[UI]: https://github.com/mandarius-dev/arm_user_interface
[spawner]: https://github.com/mandarius-dev/arm_model_spawner
[script]: https://github.com/mandarius-dev/arm_matlab_scripts
[control]: https://github.com/mandarius-dev/arm_control
[model]: https://github.com/mandarius-dev/arm_3d_model
