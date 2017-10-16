# Notes


第10章 理解Session 和Cookies


Cookie占用网络带宽，所以处理多连接希望用session，但是session不易在多服务器共享

Cookie: Key/value pair that server sent to the clients which could be used for next visit


tomcat 生成并返回cookie在HTTP header中


Session: 客户数据保存在服务端，客户通过cookie只传输id 

分布式系统中cookie同步方便（因为储存在客户段）,但是会带来管理混乱，所以需要分布式的session管理系统


第11章 tomcat架构


tomcat 核心组建：connector/container

N个connector+ container形成service, server 决定tomcat 生命周期







