# Gazebo_Simulation

The following link is the simulated world running in action. 
It includes 4 drones, 3 rovers and 4 landmarks.

https://www.youtube.com/watch?v=PZsNeRNcAIM
<iframe width="560" height="315" src="https://www.youtube.com/embed/PZsNeRNcAIM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In the dataset, the ground truth position of each vehicle is included in the file 'gazebo-model_states'.
For each vehicle, its IMU data is saved under 'vehicle-mavros-imu-data'. 
Vehicles' estimated location is saved under 'vehicle-mavros-global_position-local'.

It is worth mentioning that the orientations of the vehicles are specified in quaternion.
The original ground truth positions are recorded at 1000Hz, which makes the file too big to be uploaded to GitHub.
Thus, the data has been resampled every 250 lines, which makes the frequency 4Hz. 4Hz is still sufficient for our purpose.
