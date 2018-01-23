#消息报告了操纵杆轴和按钮的状态

文件位置: sensor_msgs/Joy.msg

定义:

		Header header		#时间戳为收到控制杆数据的时间
		float32[] axes		#控制杆轴的测量数据
		int32[] buttons		#控制杆按钮的测量数据

紧凑型定义:

		std_msgs/Header header
		float32[] axes
		int32[] buttons
