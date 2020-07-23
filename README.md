# chatserver
> 可以工作在nginx tcp负载均衡环境中的集群聊天服务器和客户端源码  基于muduo实现。
> 功能：客户端新用户注册、登录；添加好友、群组；好友聊天；群组聊天；离线消息接收；nginx配置负载均衡；客户端跨服务器通信。 

# prepare 
> 运行环境：ubuntu 19.04
> 运行前，请确保已正确安装muduo、nginx、redis、MySQL、CMake，以及其它一些代码运行必须的组件。

# to run
![start_server](https://github.com/WWWangHan/cluster-chat-server/blob/master/readme_img/start_server.png)
> 启动服务器，需要提前配置好nginx的负载控制。
![start_client](https://github.com/WWWangHan/cluster-chat-server/blob/master/readme_img/start_client.png)
> 启动客户端。
![check_mysql](https://github.com/WWWangHan/cluster-chat-server/blob/master/readme_img/check_mysql.png)
> 查看mysql中用户信息。
![user_login](https://github.com/WWWangHan/cluster-chat-server/blob/master/readme_img/user_login.png)
> 用户登录。
![chat](https://github.com/WWWangHan/cluster-chat-server/blob/master/readme_img/chat.png)
> 因为nginx的负载均衡设置为轮询，所以两个用户也可以实现跨服务器聊天，
![user_status_update](https://github.com/WWWangHan/cluster-chat-server/blob/master/readme_img/user_status_update.png)
> 用户登录成功以后，状态会得到更新。

# more
> 在注册、登录成功以后，其余的功能，用户可以按照提示，自行使用。
