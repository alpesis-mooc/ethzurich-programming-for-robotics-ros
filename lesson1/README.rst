##############################################################################
Husky
##############################################################################

- download: http://wiki.ros.org/husky_gazebo/Tutorials/Simulating%20Husky
- ros commands:

::

    $ roslaunch husky_gazebo husky_empty_world.launch world_name:=worlds/willowgarage.world
    $ rosnode list
    $ rqt_graph

- download: http://wiki.ros.org/teleop_twist_keyboard

::

    $ sudo apt-get install python-catkin-tools
    $ catkin build <package> 
