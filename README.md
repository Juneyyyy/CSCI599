## User safety: Stabilizing an Aggressively Thrown Drone

## Introduction
A holodeck is an immersive 3D representation with real and virtual objects. Drones have been gaining popularity in the field of Holodecks. Drone sizes range from millimeters to meters. Given drones' compact size, a soft throw can easily damage them. When a drone suddenly becomes uncontrollable, the drone can injury a human. The project is focus on how to recalibrate a drone when it is aggressively thrown without injuring the people around the drone and the drone itself. 


## Setup
The drone bought is a DJI Tello. The interface with the drone is by using the DJI Tello APP on the iPhone to configure the IMU and PyCharm to configure the movements through WiFi. To connect to the iPhone, the mobile data must be turned off; to connect to the laptop, the public firewall must be turned off.  Then remove the propeller and propeller shield to configure the IMU. Open the iPhone app, click on the gear, go to more, click the triple period, and click the calibrate on the IMU status. Follow the instructions to place the drone in the proper orientation for configuration. Lastly, connect the drone to the laptop for the proper application.


## Install using pip
```
pip install djitellopy
```

### API Reference
See [djitellopy.readthedocs.io](https://djitellopy.readthedocs.io/en/latest/) for a full reference of all classes and methods available.

## Link to the presentation and Demo
[Presentation link](https://docs.google.com/presentation/d/1P0m3uzEY-Vi8pXtksyWS5TmHN1pD7XP-A5JoB5ucC9U/edit?usp=sharing)
