# NasaRmc2019

This is the primary codebase for all of the TrickFire Robotics Nasa RMC 2019 competition entry.

# Clone the repo
```bash
git clone --recurse-submodules https://github.com/TrickfireRobotics/NasaRmc2019.git
cd NasaRmc2019
git submodule update --init --recursive
```

# Installation
```bash
./apt_install_dependencies.sh
./install_opencv_and_contrib.sh
./install_librealsense.sh
source /opt/ros/kinetic/setup.bash
./build_all.sh
```
