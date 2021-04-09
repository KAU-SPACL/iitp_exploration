# iitp_Exploration


- - -
## Empty Space Detection + A*

### waypoint_generation_ptHCloud_mapdata_filtering_final    
Subscribe pointcloud data, position and publish 3D A* path   
Main ROS topic : /rtabmap/cloud_map, /rtabmap/odom => /optimal_path_x, y, z 
![waypoint_generation_ptCloud_mapdata_filtering_final](https://user-images.githubusercontent.com/41814103/113669415-b354e400-96ee-11eb-987f-e9fd88967925.png)


### depth_multiview_image_200917_r4
Subscribe pointcloud data, position and publish image of projected pointcloud.
Main ROS topic : /rtabmap/cloud_map, /rtabmap/odom => /image_front, /image_back, /image_right, /image_left

![depth_multiview_image_200917_r4](https://user-images.githubusercontent.com/41814103/113669414-b2bc4d80-96ee-11eb-9179-aefee032d8f0.png)





#### 공개 SW 요약서
![요약서2](https://user-images.githubusercontent.com/41814103/114132430-500dc080-993f-11eb-9569-2be06eeebe82.JPG)
