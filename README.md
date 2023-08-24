# cpr_office_extension_gazebo
Extension of the original gazebo office environment by Clearpath Robotics, with textured objects, larger rooms, and more features.

## Usage
### Installation:
```
cd ~/catkin_ws/src/
git clone https://github.com/QVPR/cpr_office_extension_gazebo.git
cd ~/catkin_ws/
catkin_make --pkg cpr_office_extension_gazebo
source ~/catkin_ws/devel/setup.bash
```
### RViz:
```
roslaunch cpr_office_extension_gazebo view_office_world.launch
```
### Gazebo:
```
roslaunch cpr_office_extension_gazebo gazebo.launch
```
## Edits
Pull requests are welcome.
### Blender file:
cpr_office_extension_gazebo/meshes/cpr_extension.blend

