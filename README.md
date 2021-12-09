# Gazebo_Simulation

The following link is the simulated world running in action. 
It includes 4 drones, 3 rovers and 4 landmarks.

[![Simulated gazebo world with drones rovers and landmarks](images/Thumbnail.png)](https://www.youtube.com/watch?v=PZsNeRNcAIM)

https://www.youtube.com/watch?v=PZsNeRNcAIM

In the dataset, the ground truth position of each vehicle is included in the file 'gazebo-model_states'.
For each vehicle, its IMU data is saved under 'vehicle-mavros-imu-data'. 
Vehicles' estimated location is saved under 'vehicle-mavros-global_position-local'.

It is worth mentioning that the orientations of the vehicles are specified in quaternion.
The original ground truth positions are recorded at 1000Hz, which makes the file too big to be uploaded to GitHub.
Thus, the data has been resampled every 250 lines, which makes the frequency 4Hz. 4Hz is still sufficient for our purpose.

The trajectory of each vehicle is plotted.
The trajectory of the drones are plotted in 3D. Whereas the trajectory of the rovers are plotted in 2D, since they only have planar motion.

![Alt text](images/trajectory_of_drone1.png?raw=true) 
![Alt text](images/trajectory_of_drone2.png?raw=true) 
![Alt text](images/trajectory_of_drone3.png?raw=true) 
![Alt text](images/trajectory_of_drone4.png?raw=true) 
![Alt text](images/trajectory_of_rover5.png?raw=true) 
![Alt text](images/trajectory_of_rover6.png?raw=true) 
![Alt text](images/trajectory_of_rover7.png?raw=true) 



The UWB ranging measurement from each vehicle is also plotted.

![Alt text](images/uwb_ranging_measurement_from_drone1.png?raw=true) 
![Alt text](images/uwb_ranging_measurement_from_drone2.png?raw=true) 
![Alt text](images/uwb_ranging_measurement_from_drone3.png?raw=true) 
![Alt text](images/uwb_ranging_measurement_from_drone4.png?raw=true) 
![Alt text](images/uwb_ranging_measurement_from_rover5.png?raw=true) 
![Alt text](images/uwb_ranging_measurement_from_rover6.png?raw=true) 
![Alt text](images/uwb_ranging_measurement_from_rover7.png?raw=true) 



