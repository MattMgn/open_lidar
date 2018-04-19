## MAPPING avec rosbag
roslaunch open_lidar gmapping_handle.launch 

## LASER MATCH avec rosbag
roslaunch open_lidar lasermatcher_handle.launch 
(avec   <param name="/use_sim_time" value="true"/> )

## LOCALIZATION avec rosbag 
roslaunch open_lidar localization_handle_rosbag.launch 

