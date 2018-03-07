#消息定义了包含不确定性的速度量,协方差矩阵按行分别表示

沿x方向速度的不确定性，沿y方向速度的不确定性，沿z方向速度的不确定性

绕x转动角速度的不确定性，绕y转动角速度的不确定性，绕z转动角速度的不确定性

位置: geometry_msgs/TwistWithCovariance.msg

定义:

		Twist twist
		float64[36] covariance		#分别表示[x;y;z;Rx;Ry;Rz]

紧凑型定义:

		geometry_msgs/Twist twist
		float64[36] covariance
