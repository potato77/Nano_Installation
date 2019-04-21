# Nano_Installation

1.Install ROS

http://wiki.ros.org/melodic/Installation/Ubuntu


2.Install Mavros Package (Binary installation)

ROS repository has binary packages for Ubuntu x86, amd64 (x86_64) and armhf (ARMv7). Kinetic also support Debian Jessie amd64 and arm64 (ARMv8).

Just use apt-get for installation:
sudo apt-get install ros-melodic-mavros ros-melodic-mavros-extras

Then install GeographicLib datasets by running the install_geographiclib_datasets.sh script:
wget https://raw.githubusercontent.com/mavlink/mavros/master/mavros/scripts/install_geographiclib_datasets.sh
./install_geographiclib_datasets.sh

sudo chmod 777 ./install_geographiclib_datasets.sh

sudo ./install_geographiclib_datasets.sh

https://github.com/mavlink/mavros


