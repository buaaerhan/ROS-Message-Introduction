#消息定义了来自外部时钟的时间基准

文件位置: sensor_msgs/TimeReference.msg

消息定义:

		Header header
		time time_ref		#外部时钟源对应的时间
		string source		#时钟源的名称(可选项)

紧凑型定义:

		std_msgs/Header header
		time time_ref
		string source
