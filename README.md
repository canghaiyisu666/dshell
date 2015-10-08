# dshell
基于原生的yarn-distributedshell上的二次开发

将普通的java程序提交到yarn上执行，通过yarn进行统一的资源管理调度。

增加了参数-container_files 和 -container_archives 用来向每一个container中传输java执行所需的文件和目录。

删除参数-num_containers并且指定为1.
