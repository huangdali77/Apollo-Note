# Apollo 2.0阅读笔记

本文档主要介绍Apollo 2.0软件平台，其中各个模块结构与功能的纤细介绍。文档的目录结构为：

- Apollo 2.0 软件结构简介
	- 软件结构图
	- 感知模块: Perception
	- 预测模块: Prediction
	- 路由模块: Routing
	- 规划模块: Planning
	- 控制模块: Control
	- 控制区域网络模块: CanBus
	- 高精地图模块: HD-Map
	- 定位模块: Localization
- 感知模块笔记
	- 代码层次结构
		- Topic注册管理器初始化
		- ShareData共享数据类初始化
		- SubNode子节点类初始化
		- DAG有向图初始化
		- DAG整体运行实现感知
	- 障碍物感知: 3D Obstacles Perception
		- 激光测距仪障碍物感知: LiDAR Obstacle Perception
		- 雷达障碍物感知: RADAR Obstacle Perception
		- 障碍物结果融合: Result Fusion
	- 信号灯感知: Traffic Light Perception
		- 信号灯预处理: Traffic Light Preprocess
		- 信号灯处理: Traffic Light Process

Links:

- [Apollo 2.0 软件结构简介](https://github.com/YannZyl/Apollo-Note/blob/master/docs/apollo_software_arch.md)
- [感知模块: 代码层次结构](https://github.com/YannZyl/Apollo-Note/blob/master/docs/perception_software_arch.md)
- [感知模块: 障碍物感知3D Obstacles Perception](https://github.com/YannZyl/Apollo-Note/blob/master/docs/perception_obstacles.md)(待完善)
- [感知模块: 信号灯感知Traffic Light Perception](https://github.com/YannZyl/Apollo-Note/blob/master/docs/perception_traffic_lights.md)
- 高精地图模块(待完善)
- Apollo坐标系研究(待完善)
- Apollo代码宏介绍(待完善)

References：

- 感知模块：相机标定 Camera Calibration(待完善)
- [感知模块：ROS tf坐标系介绍](http://wiki.ros.org/tf/Tutorials#Learning_tf)
- [感知模块：ROS tf坐标系转换Example](http://wiki.ros.org/navigation/Tutorials/RobotSetup/TF)
- [感知模块：ROS&&PCL PointCloud点云介绍](http://wiki.ros.org/pcl/Overview)
- [感知模块：扫描线算法](https://www.jianshu.com/p/d9be99077c2b)
- [感知模块：并查集算法](https://www.cnblogs.com/shadowwalker9/p/5999029.html)
- [感知模块：二分图匹配-匈牙利算法](https://en.wikipedia.org/wiki/Hungarian_algorithm)