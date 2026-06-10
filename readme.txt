修改 trigger.txt 内容, 内容分为两部分，中间使用空格隔开。例如：
homeassistant/home-assistant:2024.6  registry.cn-hangzhou.aliyuncs.com/yaming116/home-assistant:2024.6
# 说明：
	• 空格前面是需要同步的镜像
	• 空格后面是上传到阿里云地址的镜像，以 / 为分割:
		• 第一部分是阿里云容器镜像仓库地址
		• 第二部分是我们自己的命名空间地址
		• 最后就是镜像名称和版本
		
** 目前每次代码提交都会触发镜像同步，需要注意
————————————————
版权声明：本文为CSDN博主「dragon434」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/dragon434/article/details/141397957