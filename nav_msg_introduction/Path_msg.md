#文件描述了Path Message相关的定义

文件位置: nav_msgs/Path.msg

原始定义:

		#存储位姿的数组，表示机器人所要走的路径
		Header header
		geometry_msgs/PoseStamped[] poses

或者定义为:

		std_msgs/Header header
		geometry_msgs/PoseStamped[] poses
