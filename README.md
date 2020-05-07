# wvp
WEB VIDEO PLATFORM是一个基于GB28181-2016标准实现的网络视频平台，目前只实现了核心信令部分，支持NAT穿透，支持海康、大华、宇视等品牌的IPC、NVR、DVR接入。
流媒体服务基于ZLMediaKit-https://github.com/xiongziliang/ZLMediaKit  
前端展示基于MediaServerUI-https://gitee.com/kkkkk5G/MediaServerUI。

# 应用场景：
主要应用在IPC等设备没有固定IP地址，但需要在互联网中观看的场景。  
要求IPC设备可以访问互联网，有云服务器用于部署本服务。

# 目前版本暂只支持：
1、视频预览  
2、云台控制（方向控制、缩放控制）  
3、视频设备信息同步  
4、离在线监控  

# 后续逐步支持：
1、安全认证  
2、录像查询与回放（基于NVR\DVR）  
3、语音对讲  
4、上级级联  
5、集群部署  

项目部署文档参考wiki说明
