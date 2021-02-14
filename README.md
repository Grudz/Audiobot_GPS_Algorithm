# Audibot GPS Algorithm - ROS

## By: Ben Grudzien

### Overview

The goal was to drive through all the GPS waypoints in under 45 seconds to get an A on the assignment. I completed it in 43 seconds earning an A. 

This project demonstrates an autonomous vehicle navigation algorithm. This algorithm utilizes the latitude and longitude of 8 GPS waypoints. I converted those locations to UTM coordinates. Then, I localized the autonomous Audi R8 based on a reference UTM coordinate, the location of the waypoint, and the location of the car. With these locations I was able to create vectors and find the angle of the car relative to the next waypoint using the dot product formula between the vectors. 

### Cool GIF of this project

![](https://github.com/Grudz/Audiobot_GPS_Algorithm/blob/main/audi_bot_gps_sim_2.gif)
