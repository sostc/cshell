# cshell
客户端client是发给客户执行的，需要帮助的人同时启动一个控制端controller，client执行的任何命令，都实时同步conroller，同时controller执行命令，命令后台发送到客户端执行，并且双方都同步显示命令输入，和命令执行结果。

客户端和控制端，通过server通讯
客户端和服务端输入相同密码后，建立链接，客户端才生效，任何一方退出，两端都失效，另外一端进入等待重联


## cshell_client

## cshell_server

## cshell_controller
