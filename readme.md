##源码阅读日志

### day 1, 2016年11月18日00:46:05
	增加了./socket/readme.md
	准备将readme.md作为笔记，记录linux内核网络协议栈源码剖析的过程
### day 2, 2016年11月18日20:24:07
	增加了对sys_socket(), sock_create, __sock_create(), inet_create()的完全注释
	socket的创建过程已经完成，接下来就要对绑定函数完成剖析
### day 3, 2016年11月19日23:57:15
	完成了sys_bind(), inet_bind() 的完全注释
### day 4, 2016年11月20日22:43:03
	sys_listen(), inet_listen(), inet_csk_listen_start(),都已经完成
	接下来就是 accept 系统调用
### day 5, 2016年11月21日20:18:24
	sys_accept(), inet_accept(), inet_csk_accept()完成！
	赶紧吃饭啦！饿死啦！
### day 6, 2016年11月23日00:44:23
	下雪了，shiiiiiiiiit!
	感冒了，shiiiiiiiiit!
	只完成了tcp的connect，shiiiiiiiiit!
### day 7, 2016年11月23日23:17:25
	connect done!
### day 8, 2016年11月24日20:21:51
	shutdown down :-)
### day 9, 2016年11月26日00:31:04
	close, 太多了我的天老爷！
### day 10, 2016年11月28日20:53:14
	先把套接字层的数据结构梳理一下，做起来应该会更轻松
### day 11, 2016年12月01日23:58:20
	修改了一些错误，并且更改了数据结构markdown的现实形式