# common_lib
　The common library for other Lidar Perception packages.

## Functions list

### Tools
+ Self-defined types, _[more](./include/common_lib/types)_.
    + PCL convenient structures, _[more](./include/common_lib/types/type.h#L10)_.
    + Parameters (`yaml`) structures, _[more](./include/common_lib/types/type.h#L74)_.
    + Constructed `Object` structure, _[more](./include/common_lib/types/object.hpp)_.
+ Compare and display functions, _[more](./include/common_lib/common.hpp)_.
+ Timer helper class, run-time statistics, _[more](./include/common_lib/time.hpp)_.
+ Point Cloud, Point, Object, etc, 3D Transform helping functions, _[more](./include/common_lib/transform.hpp)_.
+ Compute 3D geometry information, _[more](./include/common_lib/geometry.hpp)_.
+ ROS Parameters (in `yaml`) loading functions, _[more](./include/common_lib/parameter.hpp)_.
+ ROS rviz processing results publisher, _[more](./include/common_lib/publisher.hpp)_.
+ 2D & 3D bounding box process functions, _[more](./include/common_lib/bounding_box.hpp)_.
+ Colors defined for rviz visualization, _[more](./include/common_lib/color.hpp)_.

### Algorithms
+ A high-performance 2D `surface::ConvexHull` for Point Cloud, _[more](./include/common_lib/algos/convex_hullxy.hpp)_.
+ Graph Algorithms, _[more](./include/common_lib/algos/graph.hpp)_.
+ Google's Hungarian Optimizer, _[more](./include/common_lib/algos/hungarian_bigraph_matcher.hpp)_.
