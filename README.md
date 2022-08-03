<div align="center">

# PoseIt Dataset

**PoseIt is a visual tactile dataset of various objects with diffferent holding poses.**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa] &nbsp; [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
  
<img src="https://github.com/CMURoboTouch/PoseIt/blob/main/figures/object_set.PNG" width="600px">
  
---
<p align="center">
<a href="https://www.google.com">Website</a> •
<a href="#dataset-format">Dataset Format</a> •
<a href="#objects">Objects</a> •
<a href="#license">License</a> •
<a href="#maintainers">Maintainers</a>
</p>
 
</div>
PoseIt dataset contains RGB-D, tactile - Gelsight & WSG-DSA, force, torque, joint angle, joint velocity, and gripper force data for various grasp holding
poses. In total, PoseIt consists of 1840 grasp datapoints collected from 26 distinct objects, with 16 different holding poses for each object. The PoseIt
data collection pipeline contains the following phases: grasping the object, moving the object to a holding pose, and shaking the object to check its
stability. To test grasp quality on a diverse range of objects, we collected data for 26 various household objects with a diverse range of size, shape,
material, mass, and texture.

- **Dataset** - [](www.google.com)
- **Paper** - [](www.google.com)

## Dataset Format
<p align="center">
<img src="https://github.com/CMURoboTouch/PoseIt/blob/main/figures/data_modalities-1-1.png" width="800px"> 

</p>

Visualization of the data collection setup and data modalities. We use a Universal Robotics UR5e 6-DoF robot arm. An OnRobot Hex 6-Axis force/torque (F/T) sensor is attached to the end effector and records F/T measurements of the grasped objects. We use a high resolution visuo-tactile GelSight sensor. We use the Servo-electric 2-finger parallel gripper WSG50 from Weiss Robotics to attach these tactile sensors. We utilize two Azure Kinects and one RGB camera to visually capture the robot's workspace. 

## Objects

| Object  | Image | Mass |
| ------------- | ------------- | ------------- |
| Hand Sanitizer  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 61g |
| Flashlight  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102940.jpg)  | 87g |
| Light Rubber Ball  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102948.jpg)  | 124g |
| Bangle  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102957.jpg)  | 23g |
| Notebook | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_103005.jpg)  | 139g |
| Tissue Paper Roll  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_103015.jpg)  | 79g |
| Rubik Cube  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 77g |
| Mustard Bottle  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 43g |
| Cooking Spoon  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_104356.jpg)  | 76g |
| Duct Tape  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 226g |
| Tongs  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 129g |
| Soft Toy  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 146g |
| Spray Deodorant  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 69g |
| Wood House  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 110g |
| Wiper  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_104349.jpg)  | 74g |
| Fork  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 32g |
| Digital Timer  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 85g |
| Storage Tray  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_104254.jpg)  | 58g |
| Buttercup Container  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_104031.jpg)  | 82g |
| Cup  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 114g |
| Glue Bottle  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_104341.jpg)  | 236g |
| Shampoo Rinser  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 85g |
| Air Quality Monitor  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 153g |
| Bowl  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 138g |
| Toothpaste  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 180g |
| Computer Mouse  | ![](https://github.com/CMURoboTouch/PoseIt/blob/main/objects/IMG_20210209_102931.jpg)  | 84g |

## License

## Maintainers
- [Shubham Kanitkar](skanitka@andrew.cmu.edu)
- [Helen Jiang](helenjia@andrew.cmu.edu)
- [Wenzhen Yuan](wenzheny@andrew.cmu.edu)

## TODO
- [x] Finalize readme poster
- [x] Add objects list
- [x] Include and describe data collection setup   
- [ ] Finalize website and link it here
- [ ] Replace object images with correct ones
- [ ] Describe dataset directory structure in tree format
- [x] Talk to Wenzhen about the License
