# [Repo 명]
Short one-line description.
예: MPC-based Whole-Body Controller for Humanoid Robots.

## Overview
이 저장소는 [로봇 이름/시뮬레이터]에서 [제어 방법]을 구현한 ROS 2 패키지입니다.
본 연구는 [논문명/프로젝트명]의 일부로 수행되었습니다.

## Dependencies
- ROS 2 Humble (>= 2022.05)
- Python 3.10 / C++17

```bash
git clone https://github.com/pitin-ev/isaacsim-docker.git
cd isaacsim-docker
```

## Installation
```bash
mkdir -p ~/ros2_ws/src && cd ~/ros2_ws/src
git clone https://github.com/<org>/<repo>.git
cd ~/ros2_ws
colcon build --symlink-install
source install/setup.bash
```

## Usage
```bash
ros2 launch <package_name> sim.launch.py world:=lab_world
ros2 run <package_name> mpc_controller --ros-args -p horizon:=30
```

## Examples
```bash
ros2 launch <package_name> sim.launch.py world:=lab_world
ros2 run <package_name> mpc_controller --ros-args -p horizon:=30
```

## Contact
Maintainer: **[성명] - email**
**Please leave any questions/issues as GitHub Issues!**

