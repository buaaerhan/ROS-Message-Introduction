# 从多反射平面激光测距仪器得到的扫描数据

文件位置: sensor_msgs/MultiEchoLaserScan.msg

消息定义:

		Header header			#时间戳为接收到第一束激光的时间
		float32 angle_min		#扫描起始的角度(rad)
		float32 angle_max		#扫描结束的角度(rad)
		float32 angle_increment	#两次测量之间的角度增量(rad)

		float32 scan_time		#两次扫描之间的时间间隔(s)

		float32 range_min		#测距最小范围(m)
		float32 range_max		#测距最大范围(m)

		LaserEcho[] ranges		#测量值，如果值超出了[range_min,range_max]范围，或者为NaN，则舍弃

		LaserEcho[] intensities	#强度测量数据，单位取决于具体的测量设备，如果未提供此数据，则数组为空

紧凑型定义:

		std_msgs/Header header
		float32 angle_min
		float32 angle_max
		float32 angle_increment
		float32 time_increment
		float32 scan_time
		float32 range_min
		float32 range_max
		sensor_msgs/LaserEcho[] ranges
		sensor_msgs/LaserEcho[] intensities

