# Lemniscate EDScorbot DataSset

In geometry, the lemniscate of Bernoulli is a plane curve defined from two given points F1 and F2, known as foci, at a distance 2c from each other as the locus of points P so that PF1·PF2 = c2. See the following figure.

![image](https://github.com/RTC-research-group/LemniscateEDScorbotDS/assets/15526602/bf02c8e9-e103-46a2-9239-2919bdd5e2cf)

We need to express these curves in 3D and play with their parameters to have a set of feasible trajectories to be executed by a robotic arm.

![image](https://github.com/RTC-research-group/LemniscateEDScorbotDS/assets/15526602/08ba0623-dc6c-40bc-8121-2151f2a05719)

These eight-shaped curves are commonly used in robotics to test and measure a robotic arm's effectiveness. The end-effector of these robots can be programmed to "draw" in their working area these curves.

To previously validate that our selected lemniscates can be reproduced in the robot, we have tested them using the visual-kinematics tools adapted for our robot and applying the limitations of the working area that we have in our lab.

![image](https://github.com/RTC-research-group/LemniscateEDScorbotDS/assets/15526602/ad439186-4042-4807-9bf9-285741197768)

We have collected different types of information from the ED-Scorobt robotic arm using a set of lemniscates. 

The ED-Scorbot is described in :

# Dataset

It is composed of several items, as expresed in this picutre:

![image](https://github.com/RTC-research-group/LemniscateEDScorbotDS/assets/15526602/a6b4cd88-9f09-4818-bd31-bc00671ef1c0)


MP4 video files are for the X, Y and Z views of the setup. They have been recorded with IP-CAMs
![image](https://github.com/RTC-research-group/LemniscateEDScorbotDS/assets/15526602/e327bb7b-8025-4e84-9c6e-dc574695ea01)

Target trajectory and recorded trajectory as npy files.

<img width="350" alt="image" src="https://github.com/RTC-research-group/LemniscateEDScorbotDS/assets/15526602/c5af8329-d05e-463e-acb6-de43dde6222b">

![image](https://github.com/RTC-research-group/LemniscateEDScorbotDS/assets/15526602/c43a505d-7523-4f20-a556-92f9065e07e5)

AEDAT files with spiking information of the SPID controllers for 4 joints of the ED-Scorbot.

![image](https://github.com/RTC-research-group/LemniscateEDScorbotDS/assets/15526602/42ffbe80-e9fa-4d61-ab7e-b03622e6a1a7)

Each trajectory is stored in a different folder according to these rules:
- AEDATs:
-   ZYNQ/Lemniscates/AEDATs/weight/end-effector-Pitch-Yall-Roll/Center/orientation-scale/numberPoints/WaitTimeMs
- NPYs and MP4:
-   ZYNQ/Lemniscates/NPYs_MP4/weight/end-effector-Pitch-Yall-Roll/Center/orientation-scale/numberPoints/WaitTimeMs

# Link to access:  

https://artuditu.eii.us.es:15623/share.cgi?ssid=7c2cec39353f405ea2b6ee1db7216040 

It requires a password to access it. Please, send an email to alinares@atc.us.es or contact through github.
