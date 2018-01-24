#表示空间中含有不确定性的位姿信息

位置: geometry_msgs/PoseWithCovariance.msg

定义:

		Pose pose
		float64[36] covariance		#6*6的矩阵，表示位姿不确定性，按行[x;y;z;Rx;Ry;Rz]

紧凑型定义:

		geometry_msgs/Pose pose
		float64[36] covariance
