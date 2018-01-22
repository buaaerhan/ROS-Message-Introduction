#本文档描述了nav_msgs中各消息类型的详细定义

**GridCells**

文件: nav_msgs/GridCells.msg

消息定义：

		Header header
		float32 cell_width
		float32 cell_height
		geometry_msgs/Point[] cells

或者定义如下：

		std_msgs/Header header
		float32 cell_width
		float32 cell_height
		geometry_msgs/Point[] cells

