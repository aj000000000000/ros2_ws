# MET0310 ROS2 workspace

yea

## How to use

1. (optional) Create a new world with `gazebo` and save it in `my_robot_controller/worlds/my_custom_world.world`
2. Build the workspace and set up environment: `./build_ws.sh`
3. Run the mapping process: `ros2 launch my_robot_controller start_mapping.launch.py`
4. Wait for the mapping process to finish
5. Save the map: `ros2 run nav2_map_server map_saver_cli -f ./my_robot_controller/maps/map`