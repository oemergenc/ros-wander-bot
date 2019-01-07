FROM mjenz/ros-turtlebot 

USER root
RUN echo 'root:root' | chpasswd
RUN apt-get update && \
    apt-get install -y terminator libgl1-mesa-glx libgl1-mesa-dri && \
    apt-get install -y ros-indigo-turtlebot-gazebo && \
    apt-get install -y ros-indigo-turtlebot ros-indigo-turtlebot-apps ros-indigo-turtlebot-interactions ros-indigo-turtlebot-simulator ros-indigo-kobuki-ftdi ros-indigo-rocon-remocon ros-indigo-rocon-qt-library ros-indigo-ar-track-alvar-msgs && \
    apt-get install -y ros-indigo-ar-track-alvar* imagemagick python-empy


USER ros
