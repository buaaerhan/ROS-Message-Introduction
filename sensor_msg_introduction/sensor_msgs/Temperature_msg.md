#消息表示从温度传感器中读取的数据

文件位置: sensor_msgs/Temperature.msg

消息定义:

		Header header
		float64 temperature		#单位为摄氏度
		float64 variance		#测量方差阵，0表示方差未知

紧凑型定义:

		std_msgs/Header header
		float64 temperature
		float64 variance
