#测量磁场强度,同时给出测量的协方差阵

文件位置: sensor_msgs/MagneticField.msg

定义:

		Header header			#时间戳为测量磁场时的时间

		geometry_msgs/Vector3 magnetic_field	#磁感应强度的x,y,z分量，NaN代表没有这个方向分量

		float64[9] magnetic_field_covariance	#测量协方差阵，0表示协方差量未知

紧凑型定义:

		std_msgs/Header header
		geometry_msgs/Vector3 magnetic_field
		float64[9] magnetic_field_covariance
