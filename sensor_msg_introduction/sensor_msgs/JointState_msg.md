#本消息描述各连接节点的状态，包括位置、速度以及加在其上的力和力矩等

文件位置: sensor_msgs/JointState.msg

定义:

		Header header
		string[] name
		float64[] position
		float64[] velocity
		float64[] effort

紧凑型定义:

		std_msgs/Header header
		string[] name
		float64[] position
		float64[] velocity
		float64[] effort
