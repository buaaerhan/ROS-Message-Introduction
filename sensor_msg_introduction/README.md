#本文件夹下主要介绍了在sensor_msgs包中的消息类型及其定义

#本文档对各消息进行了简介

		消息类型				作用

		BatteryState			检测电池状态
		CameraInfo				相机图片信息
		ChannelFloat32			为PointCloud消息提供可选数据,作为PointCloud的子类型
		CompressedImage			包含一张压缩图像
		FluidPressure			定义流体压强，可能是大气压、水压等
		Illuminance				显示光强信息，光强的测量是沿着传感器X轴正方向的
		Image					包含一张未经压缩的图像
		Imu						包含惯性元件IMU数据，加速度单位m/s^2,角速度单位rad/s
		JointState				存储关节处的状态数据，位置、速度、力、力矩等
		Joy						报告控制杆轴和按钮的状态
		JoyFeedback				定义操纵杆的反馈类型、id以及反馈值
		JoyFeedbackArray		一次性发布多个反馈
		LaserEcho				作为MultiEchoLaserScan的子类型，一般不会单独使用
		LaserScan				激光扫描数据，此消息类型只适配激光扫描传感器，其它传感器需另定义消息
		MagneticField			测定给定地点的磁场
		MultiDOFJointState		表示多自由度关节的状态
		MultiEchoLaserScan		多重反馈的激光扫描数据
		NavSatFix				GPS定位信息，参考系为WGS84
		NavSatStatus			卫星定位状态，是否定位成功以及所采用的定位系统
		PointCloud				本消息保存了一系列3D点的位置，以及每个点对应的额外信息
		PointCloud2				包含一系列N维点，还可能包含一些额外信息，如模、强度等
		PointField				以PointCloud2中的格式描述点
		Range					从测距设备中读取的测距信息
		RegionOfInterest		标定一幅图片中的感兴趣区域
		RelativeHumidity		从相对湿度计中读取的相对湿度数值
		Temperature				从温度计中读取的温度值
		TimeReference			从外部时钟读取的参考时间


