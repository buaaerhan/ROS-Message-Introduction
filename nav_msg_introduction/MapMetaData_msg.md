#本文档描述了nav_msgs中各消息类型的详细定义

**MapMetaData**

文件: nav_msgs/MapMetaData.msg

消息定义:

		time map_load_time #地图加载的时间
		float32 resolution #地图分辨率[m/cell]
		uint32 width       #地图宽度[cells]
		uint32 height      #地图高度[cells]
		geometry_msgs/Pose origin #地图原点

或者定义如下:

		time map_load_time
		float32 resolution
		uint32 width
		uint32 height
		geometry_msgs/Pose origin

