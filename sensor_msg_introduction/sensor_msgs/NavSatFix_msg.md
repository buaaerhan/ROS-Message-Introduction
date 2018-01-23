#定义卫星导航定位消息,使用WGS84坐标系

文件位置: sensor_msgs/NavSatFix.msg

定义:

		Header header			#时间戳为测量时的ROS时间，坐标系为天线坐标系

		NavSatStatus status		#卫星定位状态信息
		float64 latitude		#维度
		float64 longitude		#经度
		float64 altitude		#海拔高度

		float64[9] position_covariance	#定位的协方差阵

		uint8 COVARIANCE_TYPE_UNKNOWN = 0
		uint8 COVARIANCE_TYPE_APPROXIMATED = 1
		uint8 COVARIANCE_TYPE_DIAGONAL_KNOWN = 2
		uint8 COVARIANCE_TYPE_KNOWN = 3

		uint8 position_covariance_type

紧凑型定义:

		uint8 COVARIANCE_TYPE_UNKNOWN=0
		uint8 COVARIANCE_TYPE_APPROXIMATED=1
		uint8 COVARIANCE_TYPE_DIAGONAL_KNOWN=2
		uint8 COVARIANCE_TYPE_KNOWN=3
		std_msgs/Header header
		sensor_msgs/NavSatStatus status
		float64 latitude
		float64 longitude
		float64 altitude
		float64[9] position_covariance
		uint8 position_covariance_type
