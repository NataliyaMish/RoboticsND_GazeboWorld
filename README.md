# RoboticsND_GazeboWorld

This is repository for the first project of Udacity Robotics Software Engineer Nanodegree.

The repository contains the following:

* model folder:
  * robot designed in the Model Editor tool of Gazebo
  * a single floor structure designed in the Building Editor tool of Gazebo
* world folder:
  * Gazebo world file that includes the models
* script folder:
  * Gazebo World plugin C++ script. The plugin displays “Welcome to Nataliya’s World!” message as soon as the Gazebo world file is launched
  
## How to try it out?

#### Create a local directory to house the repository
```sh
$ cd /home/
$ mkdir -p /home/myworld/
```

#### Clone the repository into /home/myworld/
```sh
$ cd /home/myworld/
$ git clone https://github.com/NataliyaMish/RoboticsND_GazeboWorld.git master
```
#### Launch the world file in Gazebo to load both the world and the plugin
```sh
cd /home/workspace/myrobot/world/           
$ gazebo myapartmentworld
```
