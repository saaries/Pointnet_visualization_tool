# Pointnet_visualization_tool

- Visualization tool for 3D point clouds
- C++ code comes from charlesq34: https://github.com/charlesq34/pointnet

- charlesq34 only provide .so library (for Linux), in this repo you will find .dll so it can run on Windows.

#### How to run ####
cd project_path\Pointnet_visualization_tool

Run a randomly generated point cloud:
python show3d_points.py

Run a specific .pts file (the argv should be the .pts file path):
python show3d_points.py .\shapenetcore_partanno_segmentation_benchmark_v0\02691156\points\atrcraft4.pts



- demo for randomly generated points:

![img](https://github.com/saaries/Pointnet_visualization_tool/blob/master/resources/3dball.gif)

- demo for .pts file in pointnet dataset (it can be any .pts file)

![img](https://github.com/saaries/Pointnet_visualization_tool/blob/master/resources/plane.gif)
