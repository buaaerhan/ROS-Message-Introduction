#消息包含了从惯性原件中得到的数据，加速度为m/s^2，角速度为rad/s
#如果所有的测量协方差已知，则需要全部填充进来，如果只知道测量方差，则
#只填充协方差矩阵的对角数据即可

文件位置: sensor_msgs/Imu.msg

定义:

		Header header
		geometry_msgs/Quaternion orientation
		float64[9] orientation_covariance		#

		geometry_msgs/Vector3 angular_velocity
		float64[9] angular_velocity_covariance

		geometry_msgs/Vector3 linear_acceleration
		float64[9] linear_acceleration_covariance

紧凑型定义:

		std_msgs/Header header
		geometry_msgs/Quaternion orientation
		float64[9] orientation_covariance
		geometry_msgs/Vector3 angular_velocity
		float64[9] angular_velocity_covariance
		geometry_msgs/Vector3 linear_acceleration
		float64[9] linear_acceleration_covariance
