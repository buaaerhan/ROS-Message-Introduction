#文件介绍了Odometry消息的定义

相关文件: nav_msgs/Odometry.msg

消息原始定义:

		#消息描述了在自由空间中位置和速度的估计值
		#消息中的Pose描述应在header.frame_id中给出的坐标系中表示
		#twist描述应在child_frame_id中给出的坐标系中表示
		Header header
		string child_frame_id
		geometry_msgs/PoseWithCovariance pose
		geometry_msgs/TwistWithCovariance twist

或者定义为:

		std_msgs/Header header
		string child_frame_id
		geometry_msgs/PoseWithCovariance pose
		geometry_msgs/TwistWithCovariance twist
