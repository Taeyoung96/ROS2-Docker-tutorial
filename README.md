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

Tag information  
- [1.0](https://hub.docker.com/layers/tyoung96/ros2-foxy-nvidia/1.0/images/sha256-4c87c15b429b8787d917bf35bc604bcb414a7f2498e5c613845e59d4724c3627?context=explore)  : Ubuntu 20.04 + ROS2 foxy +  Gazebo +  Rqt  
- [1.1](https://hub.docker.com/layers/178861584/tyoung96/ros2-foxy-nvidia/1.1/images/sha256-b81681c87f0a2ee4c12346db060884749e03b04aac68cfa166551b62ed5ce3b8?context=repo) : 1.0 + image-tools + Turtlebot3 + navigation2 + [RQT icon visualize](https://answers.ros.org/question/372890/rqt-button-not-show-icon/)

I fork ROS2 tutorial code in [this repository](https://github.com/robotpilot/ros2-seminar-examples).  
