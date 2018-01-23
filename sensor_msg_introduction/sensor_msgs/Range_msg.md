#读取测量范围信息，注意此消息类型不适用于激光扫描仪

文件位置: sensor_msgs/Range.msg

消息定义:

		Header header			#时间戳是测距仪器返回距离数据的时间

		#枚举传感器类型
		uint8 ULTRASOUND=0
		uint8 INFRARED=1

		uint8 radiation_type	#传感器使用的测距手段(声波，红外等)
		float32 field_of_view	#能够有效读取距离数据的弧度大小(rad)
		float32 min_range		#最小距离值(m)
		float32 max_range		#最大距离值(m)

		float32 range			#距离测量值(m)

紧凑型定义:

		uint8 ULTRASOUND=0
		uint8 INFRARED=1
		std_msgs/Header header
		uint8 radiation_type
		float32 field_of_view
		float32 min_range
		float32 max_range
		float32 range
