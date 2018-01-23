# 描述某种流体中的压强，包括空气压强、水压等
# 注意，本消息不适配接触性压力/压强传感器

文件位置: sensor_msgs/FluidPressure.msg

定义:

		Header header			#测量的时间戳，压强传感器所在的位置即为坐标系id
		float64 fluid_pressure	#绝对压强，单位为Pa
		float64 variance		#如果测量方差未知，则设为0

紧凑型定义:

		std_msgs/Header header
		float64 fluid_pressure
		float64 variance
