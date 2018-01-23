# 多自由度关节的状态表示，每一个关节状态都可以用一个转换矩阵来表示
# 注意消息中所有的数组的大小都是相同的，或者为空

文件位置: sensor_msgs/MultiDOFJointState.msg

消息定义:

		Header header

		string[] joint_names
		geometry_msgs/Transform[] transforms
		geometry_msgs/Twist[] twist
		geometry_msgs/Wrench[] wrench

紧凑型消息定义:

		std_msgs/Header header
		string[] joint_names
		geometry_msgs/Transform[] transforms
		geometry_msgs/Twist[] twist
		geometry_msgs/Wrench[] wrench

