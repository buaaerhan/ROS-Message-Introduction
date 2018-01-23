#定义一系列3D点，以及与这些点对应的一些附加信息

文件位置: sensor_msgs/PointCloud.msg

消息定义:

		Header header			#时间戳为传感器接收数据的时间，坐标系为传感器坐标系

		geometry_msgs/Point32[] points	#3D点组成的数组,每个Point32类型都表示一个3D点

		ChannelFloat32[] channels		#每一个channel都与存点数组有相同数量的元素

紧凑型定义:

		std_msgs/Header header
		geometry_msgs/Point32[] points
		sensor_msgs/ChannelFloat32[] channels
