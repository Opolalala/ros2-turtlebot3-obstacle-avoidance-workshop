export TURTLEBOT3_MODEL=burger
~/workshop_ws/src/my_world/worlds$ ros2 run gazebo_ros spawn_entity.py -entity turtlebot3 -database turtlebot3_burger -x 0.0 -y 0.0 -z 0.0 -Y 0.0 
ros2 launch gazebo_ros gazebo.launch.py \
world:=/home/opola/workshop_ws/src/my_world/worlds/my_world.world
