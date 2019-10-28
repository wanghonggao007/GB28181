                                                      基于GB28181的简单服务器
一、介绍  
这是一个简单的基于GB28181协议的视频流服务器  
二、推流格式  
目前只支持H264裸流，后续会加上其他流格式的推流和直播  
三、配置  
1、相机配置（目前以海康为例）  
![image](https://github.com/wanghonggao007/GB28181/blob/master/x64/Release/haikangconfig.PNG)  
2、服务端配置  
[GB28181]  
_comment=相机平台sipId，端口号，ip地址  
platform_id=34020000001320000001  
platform_port=5081  
platform_ip=192.168.8.64  

Local_comment=本地平台sipId，端口号，ip地址  
local_id=34020000002000000001  
local_port=5082  
local_ip=192.168.8.2  

camera_comment=摄像头数目，sipId  
camera_num=1  
camera1_sip_id=18223002001310012922  
camera1_recv_port=6000  
camera2_sip_id=18223002001310012923  
camera2_recv_port=5502  

UserName=账号  
UserPwd= 密码  
四、程序架构图  
五、打赏  
如果您绝对这次修改和完善对您有帮助，不妨打赏一下  
![image](http://osijiy9i7.bkt.clouddn.com/%E6%94%AF%E4%BB%98.PNG)
