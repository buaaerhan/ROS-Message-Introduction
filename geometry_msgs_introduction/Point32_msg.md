#消息表示三维空间中的点的位置，与Point类型类似，但是如果可能，建议使用  
#Point代替Point32，因为Point精度高,如果不希望占用太多空间，则在满足经度  
#要求的情况下可以使用Point32

位置: geometry_msgs/Point32.msg

定义:

		float32 x
		float32 y
		float32 z
