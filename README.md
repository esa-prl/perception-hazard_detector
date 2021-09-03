# Hazard Detector Library
This package can be used to detect rocks or similar obstacles in a provided distance frame of a stereo camera.
After a first calibration, only comparisons with a look-up table are required to determine whether or not an
obstacle is in front.
Since we are usually already computing the stereo disparities for localization anyways,
this approach is computationally cheap.

**This is research code, expect that it changes often and any fitness for a particular purpose is disclaimed.**

Have a look at https://github.com/esa-prl/perception-orogen-hazard_detector to see how we use it.

## Publications
If you use this work in an academic context, please cite our publication
["Efficient Autonomous Navigation for Planetary Rovers with Limited Resources"](https://doi.org/10.1002/rob.21981)
since it explains the library, the motivation, and its greater context while also showing field test results.

```
Gerdes, L, Azkarate, M, Sánchez-Ibáñez, JR, Joudrier, L, Perez-del-Pulgar, CJ. Efficient autonomous navigation for planetary rovers with limited resources. J Field Robotics. 2020; 37: 1153: 1153– 1170. https://doi.org/10.1002/rob.21981
```

```
@article{https://doi.org/10.1002/rob.21981,
author = {Gerdes, Levin and Azkarate, Martin and Sánchez-Ibáñez, José Ricardo and Joudrier, Luc and Perez-del-Pulgar, Carlos Jesús},
title = {Efficient autonomous navigation for planetary rovers with limited resources},
journal = {Journal of Field Robotics},
volume = {37},
number = {7},
pages = {1153-1170},
keywords = {autonomy, exploration, perception, planetary robotics, planning},
doi = {https://doi.org/10.1002/rob.21981},
url = {https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.21981},
eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1002/rob.21981},
abstract = {Abstract Rovers operating on Mars require more and more autonomous features to fulfill their challenging mission requirements. However, the inherent constraints of space systems render the implementation of complex algorithms an expensive and difficult task. In this paper, we propose an architecture for autonomous navigation. Efficient implementations of autonomous features are built on top of the ExoMars path following navigation approach to enhance the safety and traversing capabilities of the rover. These features allow the rover to detect and avoid hazards and perform significantly longer traverses planned by operators on the ground. The efficient navigation approach has been implemented and tested during field test campaigns on a planetary analogue terrain. The experiments evaluated the proposed architecture by autonomously completing several traverses of variable lengths while avoiding hazards. The approach relies only on the optical Localization Cameras stereo bench, a sensor that is found in all current rovers, and potentially allows for computationally inexpensive long-range autonomous navigation in terrains of medium difficulty.},
year = {2020}
}
```
