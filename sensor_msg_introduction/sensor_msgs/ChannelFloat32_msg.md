#作为PointCloud消息的自消息类型，用以保存在云中的每个点的附加信息

文件位置: sensor_msgs/ChannelFloat32.msg

		# channel的名字可以是：
		# “u”,"v"，分别代表行和列
		# “rgb” - 立体相机所产生的点云数据
		# “intensity” - 激光或者像素的强度
		# “distance”

		string name
		float32[] values


紧凑型定义:

		string name
		float32[] values
