#本消息包含了一张未经压缩的图像,图像原点定义为(0,0)左上方

文件位置: sensor_msgs/Image.msg

消息定义:

		Header header		#时间戳为接收图像消息时的时间，坐标id是相机光学坐标系原点
		uint32 height		#图像高度，整数，表示图像行数
		uint32 width		#图像宽度，整数，表示图像列数

		string encoding		#像素编码

		uint8 is_bigendian	#数据是否按照字节顺序
		uint32 step			#行的长度
		uint8[] data		#真实矩阵数据，矩阵尺寸为(step*rows)

紧凑型定义:

		std_msgs/Header header
		uint32 height
		uint32 width
		string encoding
		uint8 is_bigendian
		uint32 step
		uint8[] data
