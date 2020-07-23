# chatserver
> 可以工作在nginx tcp负载均衡环境中的集群聊天服务器和客户端源码  基于muduo实现。
> 功能：客户端新用户注册、登录；添加好友、群组；好友聊天；群组聊天；离线消息接收；nginx配置负载均衡；客户端跨服务器通信。 

# prepare 
> 运行环境：ubuntu 19.04
> 运行前，请确保已正确安装muduo、nginx、redis、MySQL、CMake，以及其它一些代码运行必须的组件。

# to run
![start_server]()
![start_client]()
![check_mysql]()
![user_login]()
![chat]()
![user_status_update]()
