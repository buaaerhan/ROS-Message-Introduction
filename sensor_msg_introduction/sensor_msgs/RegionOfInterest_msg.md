#消息用来定义图像中的感兴趣区域，长方形，由左上角点坐标和长度、宽度定义

文件位置: sensor_image/RegionOfInterest.msg

消息定义:

		uint32 x_offset			#分别定义左上角点的x坐标和y坐标
		uint32 y_offset

		uint32 height
		uint32 width

		bool do_rectify

紧凑型定义:

		uint32 x_offset
		uint32 y_offset
		uint32 height
		uint32 width
		bool do_rectify
