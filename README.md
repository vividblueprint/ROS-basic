# Vscode setting for ROS
```
{
    "configurations": [
        {
            "name": "Linux",
            "includePath": [
                "../../**",
                "${workspaceFolder}/**",
                "/opt/ros/noetic/include/",
                "/usr/include/pcl-1.10",
                "/usr/include/eigen3"
            ],
            "defines": [],
            "compilerPath": "/usr/bin/gcc",
            "cStandard": "c17",
            "cppStandard": "gnu++14",
            "intelliSenseMode": "gcc-x64"
        }
    ],
    "version": 4
}
```

# ROS Shell Commands
```
roscd
rosls
rosed
roscp
rospd
rosd
```
# ROS Executuion Commands
```
roscore
rosrun
roslaunch
rosclean
```
# ROS Information Commands
```
rostopic    bw delay echo find hz info list pub type
rosservice  args call find info list type uri
rosnode     ping list info machine kill cleanup
rosparam    set get load dump delete list
rosbag      check compress decompress decrypt encrypt filter fix help info play record reindex
rosmsg      show info list md5 package packages
rossrv      show info list md4 package packages
rosversion  -a -d
roswtf
```
# ROS Catkin Commands
```
catkin_create_pkg
catkin_make
catkin_eclipse
catkin_prepare_release
catkin_generate_changelog
catkin_init_workspace
catkin_find
```
# ROS Package Commands
```
rospack
rosinstall
rosdep
roslocate
roscreate-pkg
rosmake
```

