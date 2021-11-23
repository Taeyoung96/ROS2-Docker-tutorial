# ROS2-Docker-tutorial

I made this repository using [athackst/vscode_ros2_workspace](https://github.com/athackst/vscode_ros2_workspace) templete with `foxy-nvidia` branch.    

You could see more information above link.    

## Prerequisites

You should already have Docker and VSCode with the remote containers plugin installed on your system.
To make nvidia driver and opengl available in docker, follow the installation instructions for docker-nvidia. 
They include the steps in docker and add the additional gpu layer. 

* [docker](https://docs.docker.com/engine/install/)
* [docker-nvidia (includes docker install and additional installation for NVidia GPU accelerated hosts)](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html#docker)
* [vscode](https://code.visualstudio.com/)
* [vscode remote containers plugin](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)  

If you have some problems, you could refer to this [link](https://github.com/athackst/vscode_ros2_workspace/tree/foxy-nvidia#error-handling-for-gpu-acceleration).  

## Environment

I made my own docker [image](https://hub.docker.com/r/tyoung96/ros2-foxy-nvidia). The packages below are available.  

- Gazebo  
- Turtlesim  
- Rqt  
- Rqt-graph  
