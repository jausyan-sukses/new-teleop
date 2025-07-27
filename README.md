## New t_EL_eop
update : using mavros_param.yaml to connect mission planner wirelles
# How to use
visit my repo to set up drone
running mission
```sh
ros2 run drone-teleop control
```
and run mavros using this command
```sh
ros2 run mavros mavros_node --ros-args --params-file ~/new-teleop/src/drone-teleop/config/mavros_param.yaml
```
