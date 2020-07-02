# RoboND-Localization-Project

Hi there! Thanks for taking a look at my project! This is the Localization project from the Udacity Robotics Software Engineer Nanodegree Program. Feel free to poke around or to download the code and give the launch files a run. The idea of the project was to build a robot model, give it sensors and actuators, and have it move and localize itself using ROS packages in a simulated Gazebo environment.

For a detailed writeup on the theory and actual development of the project, please refer to the Writeup: ``Where_Am_I_.pdf``, as this README.md will only contain instructions on how to run the code!

## Downloading the repository

Please make sure you have ROS and [Gazebo](http://gazebosim.org/tutorials?tut=install_ubuntu&ver=7.0&cat=install) installed. If you don't, please refer to the [ROS wiki](http://wiki.ros.org/Documentation) to install all required packages and tools. You will need:
* [ROS kinetic (or newer)](http://wiki.ros.org/kinetic)
* [AMCL package](http://wiki.ros.org/amcl)
* [move_base package](http://wiki.ros.org/move_base)

If you have installed all the required packages, open the terminal and navigate to your catkin workspace's source directory (might be different, but the command is usually ``cd ~/catkin_ws/src``). Run the command:
``git clone https://github.com/HumbertoMartinezBarron/RoboND-Localization-Project.git``

Once all the files have been downloaded, navigate to the top of your catkin workspace and source your setup file:
``source devel/setup.bash``

Now run
``catkin_make``
to compile the code.

If you run into trouble along the way, there might be a version issue or a problem with the required packages. Never let go of the ROS wiki. It will save you every time.

## Running the project
If all the files are ready and compiled, launch the localization environment and files from the top of your catkin workspace with the command:
``roslaunch udacity_bot udacity_world.launch``
and watch the little robot locate itself while navigating towards its goal! This will help you get started with Monte-Carlo Localization and the use of probabilistic filters! :)

Happy roboting!

By: Humberto MartinezBarron
