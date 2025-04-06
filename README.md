# 🧭 TurtleBot3 Mapping and Navigation in Gazebo (ROS 2)

This project demonstrates simulating TurtleBot3 in a custom-built Gazebo environment using ROS 2. It includes two major tasks:

1. **Mapping the environment using Cartographer SLAM**
2. **Navigating autonomously using the Nav2 stack**

---

## 📹 Demo Videos

### 🗺️ Mapping the Environment (SLAM)
[![TurtleBot3 SLAM Mapping](https://img.youtube.com/vi/7OxHPk5oFXc/0.jpg)](https://www.youtube.com/watch?v=7OxHPk5oFXc)  
In this video, TurtleBot3 uses Cartographer SLAM to explore and create a 2D occupancy grid map in a custom Gazebo world.

### 🚗 Navigation Using Nav2
[![TurtleBot3 Nav2 Navigation](https://img.youtube.com/vi/ei4HWBFNY_c/0.jpg)](https://youtu.be/ei4HWBFNY_c)  
In this video, the robot uses the previously created map to autonomously navigate through the environment using ROS 2 Nav2 stack.

---

## 🛠️ Tools & Technologies

- **Robot:** [TurtleBot3](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/)
- **Simulation:** [Gazebo](http://gazebosim.org/)
- **Middleware:** [ROS 2 Humble Hawksbill](https://docs.ros.org/en/humble/)
- **SLAM:** [Cartographer](https://google-cartographer-ros.readthedocs.io/en/latest/)
- **Navigation:** [Nav2](https://navigation.ros.org/)
