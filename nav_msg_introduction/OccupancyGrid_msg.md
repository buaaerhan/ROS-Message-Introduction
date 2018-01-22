#描述OccupancyGrid的相关信息

文件: nav_msgs/OccupancyGrid.msg

文件定义:

		#消息描述了2D网格地图，每一个cell值都代表这点被占用的概率
		Header header
		MapMetaData info
		int8[] data #地图网格被占用的概率,数值在[0-100]之间,未知区域设置为-1

或者另一重定义:

		std_msgs/Header header
		nav_msgs/MapMetaData info
		int8[] data
