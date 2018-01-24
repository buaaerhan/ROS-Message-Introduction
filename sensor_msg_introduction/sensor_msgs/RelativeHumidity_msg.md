#消息给出相对湿度传感器的数据

文件位置: sensor_msgs/RelativeHumidity.msg

消息定义:

		Header header
		float64 relative_humidity	#相对湿度,数值为[0.0~1.0]之间的数值
		float64 variance			#表示测量的方差，0表示方差未知

紧凑型定义:

		std_msgs/Header header
		float64 relative_humidity
		float64 variance
