# Robot Model

`robot_model` contains packages for modeling various aspects of robot information, specified in the Xml Robot Description Format (URDF).
The core package of this stack is urdf, which parses URDF files, and constructs an object model (C++) of the robot.

## Deprecation
This repository and the `robot_model` metapackage are deprecated.
The other packages will continue to be maintained, but are being moved to new repositories.
More information is available at [`ros/robot_model#195`](https://github.com/ros/robot_model/issues/195).

**Moved Repos**

* `collada_urdf` and `collada_parser`
    * [`ros/collada_urdf`](https://github.com/ros/collada_urdf)
* `joint_state_publisher`
    * [`ros/joint_state_publisher`](https://github.com/ros/joint_state_publisher)
* `kdl_parser` and `kdl_parser_py`
    * [`ros/kdl_parser`](https://github.com/ros/kdl_parser)
* `urdf` and `urdf_parser_plugin`
    * [`ros/urdf`](https://github.com/ros/urdf)
