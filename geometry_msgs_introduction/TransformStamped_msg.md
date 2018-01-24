#包含时间和坐标参考，同时包含子坐标系id的转换矩阵，此消息经常用在tf包中

位置: geometry_msgs/TransformStamped.msg

定义:

		Header header
		string child_frame_id	#子坐标系id名
		Transform transform

紧凑型定义:

		std_msgs/Header header
		string child_frame_id
		geometry_msgs/Transform transform
