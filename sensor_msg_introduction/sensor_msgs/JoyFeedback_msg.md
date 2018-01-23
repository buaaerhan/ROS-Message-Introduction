#消息反映了控制杆的反馈信息

文件位置: sensor_msgs/JoyFeedback.msg

定义:

		#定义反馈消息的类型
		uint8 TYPE_LED = 0
		uint8 TYPE_RUMBLE = 1
		uint8 TYPE_BUZZER = 2

		uint8 type

		#定义反馈的id，第一个反馈是1，第二个是2，...
		uint8 id

		#反馈的强度，数值在[0.0-1.0]之间
		float32 intensity

紧凑型定义:

		uint8 TYPE_LED=0
		uint8 TYPE_RUMBLE=1
		uint8 TYPE_BUZZER=2
		uint8 type
		uint8 id
		float32 intensity
