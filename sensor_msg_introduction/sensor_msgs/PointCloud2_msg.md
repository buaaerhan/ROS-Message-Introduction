#本消息保存了一个N维点，可能还会包含一些附加信息，如模、强度信息等等

文件位置: sensor_msgs/PointCloud2.msg

消息定义:

		Header header			#时间戳是传感器得到数据的时间，坐标系是传感器坐标系
		
		#定义点云的2D结构，如果云是无顺序的，则height为1，宽度就是点云的长度
		uint32 height			
		uint32 width

		PointField[] fields

		bool is_bigendian		#数据是否是字节型的
		uint32 point_step		#一个点的字节长度
		uint32 row_step			#一行总共的字节长度
		uint8[] data			#实际的点数据，大小是(row_step*height)

		bool is_dense			#如果没有无效点，则设置为True

紧凑型定义:

		std_msgs/Header header
		uint32 height
		uint32 width
		sensor_msgs/PointField[] fields
		bool is_bigendian
		uint32 point_step
		uint32 row_step
		uint8[] data
		bool is_dense
