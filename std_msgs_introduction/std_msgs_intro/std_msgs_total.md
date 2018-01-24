#本篇文档汇总了std_msgs下的所有标准类型的消息

**Bool**

位置: std_msgs/Bool.msg

定义: 

		bool data


**Byte**

位置: std_msgs/Byte.msg

定义:
	
		byte data


**ByteMultiArray**

位置: std_msgs/ByteMultiArray.msg

定义:

		MultiArrayLayout layout
		byte[] data

或:
	
		std_msgs/MultiArrayLayout layout
		byte[] data


**Char**

位置: std_msgs/Char.msg

定义:

		char data


**ColorRGBA**

位置: std_msgs/ColorRGBA.msg

定义: 

		float32 r
		float32 g
		float32 b
		float32 a


**Duration**

位置: std_msgs/Duration

定义:

		duration data


**Empty**

位置: std_msgs/Empty.msg

定义: 

		


**Float32**

位置: std_msgs/Float32.msg

定义:

		float32 data


**Float32MultiArray**

位置: std_msgs/Float32MultiArray.msg

定义:

		MultiArrayLayout layout
		float32[] data

或者:
	
		std_msgs/MultiArrayLayout layout
		float32[] data



**Float64**

位置: std_msgs/Float64.msg

定义:

		float64 data


**Float64MultiArray**

位置: std_msgs/Float64MultiArray.msg

定义:

		MultiArrayLayout layout
		float64[] data

或者:

		std_msgs/MultiArrayLayout layout
		float64[] data


**Header**

位置: std_msgs/Header.msg

定义:

		#定义时间和坐标系统
		uint32 seq		#序列id
		time stamp		#时间戳,s:ns
		string frame_id	#0代表没有参考系,1代表全局参考系


**Int16**

位置: std_msgs/Int16.msg

定义: 

		int16 data


**Int16MultiArray**

位置: std_msgs/Int16MultiArray.msg

定义:

		MultiArrayLayout layout
		int16[] data

或者:

		std_msgs/MultiArrayLayout layout
		int16[] data



**Int32**

位置: std_msgs/Int32.msg

定义:

		int32 data



**Int32MultiArray**

位置: std_msgs/Int32MultiArray.msg

定义:

		MultiArrayLayout layout
		int32[] data

或者:

		std_msgs/MultiArrayLayout layout
		int32[] data



**Int64**

位置: std_msgs/Int64.msg

定义:

		int64 data



**Int64MultiArray**

位置: std_msgs/Int64MultiArray.msg

定义: 

		MultiArrayLayout layout
		int64[] data

或者:

		std_msgs/MultiArrayLayout layout
		int64[] data



**Int8**

位置: std_msgs/Int8.msg

定义: 

		int8 data



**Int8MultiArray**

位置: std_msgs/Int8MultiArray.msg

定义: 

		MultiArrayLayout layout
		int8[] data

或者:

		std_msgs/MultiArrayLayout layout
		int8[] data



**MultiArrayDimension**

位置: std_msgs/MultiArrayDimension.msg

定义:

		string label	#给定维度的标签
		uint32 size		#给定维度的大小
		uint32 stride	#给定维度的步长



**MultiArrayLayout**

位置: std_msgs/MultiArrayLayout.msg

定义:

		#定义通用的多维数组，来表示某些数据类型
		MultiArrayDimension[] dim	#定义维度信息
		uint data_offset			#定义数据前缀

或者:

		std_msgs/MultiArrayDimension[] dim
		uint32 data_offset

注意:

multiarray(i,j,k) = data[data_offset + dim_stride[1]*i + dim_stride[2]*j + k]

例如一张3通道的640*480的图片，可以表示如下:

		dim[0].label = "height"
		dim[0].size = 480
		dim[0].stride = 3*640*480 = 921600 (dim[0]的数据前缀量就是图像尺寸)
		dim[1].label = "width"
		dim[1].size = 640
		dim[1].stride = 3*640 = 1920
		dim[2].label = "channel"
		dim[2].size = 3
		dim[2].stride = 3	#stride是从最高维度到本维度，共有多少个本维度元素



**String**

位置: std_msgs/String.msg

定义:

		string data



**Time**

位置: std_msgs/Time.msg

定义:

		time data



**UInt16**

位置: std_msgs/UInt16.msg

定义:

		uint16 data




**UInt16MultiArray**

位置: std_msgs/UInt16MultiArray.msg

定义:

		MultiArrayLayout layout
		uint16[] data

或者:

		std_msgs/MultiArrayLayout layout
		uint16[] data





**UInt32**

位置: std_msgs/UInt32.msg

定义:

		uint32 data




**UInt32MultiArray**

位置: std_msgs/UInt32MultiArray.msg

定义:

		MultiArrayLayout layout
		uint32[] data

或者:

		std_msgs/MultiArrayLayout layout
		uint32[] data




**UInt64**

位置: std_msgs/UInt64.msg

定义:

		uint64 data




**UInt64MultiArray**

位置: std_msgs/UInt64MultiArray.msg

定义:

		MultiArrayLayout layout
		uint64[] data

或者:

		std_msgs/MultiArrayLayout layout
		uint64[] data





**UInt8**

位置: std_msgs/UInt8.msg

定义:

		uint8 data




**UInt8MultiArray**

位置: std_msgs/UInt8MultiArray.msg

定义:

		MultiArrayLayout layout
		uint8[] data

或者:

		std_msgs/MultiArrayLayout layout
		uint8[] data



