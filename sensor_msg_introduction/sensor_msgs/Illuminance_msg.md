# 本消息表示所测量到的光强，测量是在传感器X轴方向进行的，也就是垂直照射到y-z平面上的光强

文件位置: sensor_msgs/Illuminance.msg

消息定义:

		Header header		#时间戳为测量光强的时间,坐标id是读取数据的位置和方向
		float64 illuminance	#测量得到的光强，单位为Lux
		float64 variance	#如果测量方差未知，则设置为0

紧凑型定义:

		std_msgs/Header header
		float64 illuminance
		float64 variance
