#本消息描述了一张压缩图像

文件位置: sensor_msgs/CompressedImage.msg

定义：

		#定义一幅压缩图像
		Header header		#Header时间戳是接收图像的时间，Header坐标id是相机的光学坐标系
		string format		#定义数据格式，支持"jpeg","png"
		uint8[] data		#压缩图像数据流

紧凑型定义:

		std_msgs/Header header
		string format
		uint8[] data
