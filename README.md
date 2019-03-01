![image](https://github.com/wangpengdc/AccessServer/blob/master/chart.jpg)
# AccessServer
  流媒体接入服务器，类似于EasyDarwin的CMS服务器功能
  主要用来对设备端以及客户端进行重定向
  本身并不具有转发功能，需要与信令/流服务器配合使用，
  AccessServer与设备端保持长连接，为客户端提供实时设备状态在线查询，
  通过redis拉去一个负载最小的对应服务的ip来进行负载均衡
