# AccessServer
  流媒体接入服务器，类似于EasyDarwin的CMS服务器功能
  AccessServer主要与device端保持长连接，为客户端提供设备状态在线查询
  根据设客户端需要的服务类型来进行对设备端以及客户端的重定向
  通过redis来进行对信令服务器以及流服务器的负载均衡
