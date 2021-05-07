# ROSBOT

本仓库建立目的是为了给同学们在ROS机器人开发中提供帮助。

国外仓库链接Github：https://github.com/Githubcxy666/ROSBOT

国内仓库链接Gitee：https://gitee.com/wybros/ROSBOT

仓库部分资料来源互联网，如有侵权，请联系邮箱 344214187@qq.com，必定在72小时内处理。

如果同学们有新资源提供分享，也请联系邮箱 344214187@qq.com。

关注微信公众号【ROS机器人开发】，获取更多ROS机器人开发资料，还有抽奖活动！

![扫码_搜索联合传播样式-标准色版2(1)](https://gitee.com/wybros/Image/raw/master/img/扫码_搜索联合传播样式-标准色版2(1).jpg)

## ROS安装

### 虚拟机ROS安装

- 
  #### 	    Kinect版本安装教程（ros init失败解决办法请看melodic版本安装）

- #### 	    melodic版本安装教程（附带ros init失败解决办法）

- #### 	[notice版本安装教程（附带ros init失败解决办法）](http://www.autolabor.com.cn/book/ROSTutorials/chapter1/12-roskai-fa-gong-ju-an-zhuang/124-an-zhuang-ros.html)

### 树莓派ROS安装

- 
  #### 	Kinect版本安装教程

- #### 	melodic版本安装教程

- #### 	notice版本安装

### Jetson nano ROS安装

- 
  #### 	Kinect版本安装教程

- #### 	melodic版本安装教程

- #### 	notice版本安装

、

## ROS开发环境搭建



## ROS相关软件安装

### [cartography安装教程](https://github.com/WLwind/cartographer_installation)



### ROS serial 串口安装教程


  - 
    #### 	Kinect版本安装教程

    `sudo apt-get install ros-kinetic-serial`

  - #### 	melodic版本安装教程

    `sudo apt-get install ros-melodic-serial`

  - #### 	notice版本安装

    `sudo apt-get install ros-notice-serial`



### vscode安装



### 串口调试软件安装


  - #### cutecom

  - #### minicom

  

### opencv安装

`pip install opencv-python`



### [teleop_twist_keyboard 键盘控制安装](https://github.com/ros-teleop/teleop_twist_keyboard)



### ROS gazebo仿真模型


  gazebo模型官方下载链接：https://github.com/osrf/gazebo_models

  为了方便大家下载，已上传到百度云盘

  关注微信公众号：ROS机器人开发

  回复  999 即可获取下载链接



### navigation功能包安装

- 
  #### 	Kinect版本安装教程

  `git clone -b kinetic-devel https://github.com/ros-planning/navigation.git`

- #### 	melodic版本安装教程

  `git clone -b melodic-devel https://github.com/ros-planning/navigation.git`

- #### 	notice版本安装

  `git clone -b noetic-devel https://github.com/ros-planning/navigation.git`



### robot_pose_ekf 安装教程

`git clone https://github.com/ros-planning/robot_pose_ekf.git`



### 雷达驱动包安装

- 
  #### 	RPLIDAR

  官方Github链接：https://github.com/Slamtec/rplidar_ros

  `git clone https://github.com/Slamtec/rplidar_ros.git`

  RPLidar A1示意图
  
  ![请输入图片描述](https://gitee.com/wybros/Image/raw/master/img/rplidar_A1.png)
  
  
  
  RPLidar A2示意图
  
  ![请输入图片描述](https://gitee.com/wybros/Image/raw/master/img/rplidar_A2.png)

## [ROS问题总汇](problems.md)



## ROS教程

以下排名不分先后

### 	ROS WIKI 

网站链接 http://wiki.ros.org/cn/ROS/Tutorials



### 	古月居

- 
  #### 		ROS入门21讲

  视频教程 https://www.bilibili.com/video/BV1zt411G7Vn

- #### ROS机器人开发案例

  视频教程 https://www.bilibili.com/video/BV1vb41177qN

- #### 		ROS机械臂开发原理

  视频教程 https://www.bilibili.com/video/BV14b411p7Hm

  

### 	中国大学MOOC --《机器人操作系统入门》


&emsp;&emsp;视频教程 https://www.bilibili.com/video/BV1PJ411D7mj?from=search&seid=367619698396859163

&emsp;&emsp;课程讲义---Gitbook：https://sychaichangkun.gitbooks.io/ros-tutorial-icourse163/content/ 

&emsp;&emsp;代码示例---Github：https://github.com/DroidAITech/ROS-Academy-for-Beginners （注意版本）



### 奥特学园 -- ROS机器人入门课程《ROS理论与实践》零基础教程


&emsp;&emsp;作者：赵虚左老师

&emsp;&emsp;视频教程 https://www.bilibili.com/video/BV1Ci4y1L7ZZ?p=1

&emsp;&emsp;课程文档 http://www.autolabor.com.cn/book/ROSTutorials/



### ROS小课堂 -- ROS快速入门课程

&emsp;&emsp;视频教程 https://space.bilibili.com/407185400/channel/detail?cid=147661



### ROS入门教程 - 创客智造

&emsp;&emsp;网站链接  https://www.ncnynl.com/archives/201608/496.html



### 深蓝学院 



### 黑马ROS无人车

&emsp;&emsp;视频教程 https://www.bilibili.com/video/BV1qh41197TZ?p=1



### 小白学移动机器人

&emsp;&emsp;课程文档 https://blog.csdn.net/zhao_ke_xue/article/details/108138981



### 小虎哥哥爱学习


&emsp;&emsp;课程文档 https://www.cnblogs.com/hiram-zhang/p/10802569.html



## ROS进阶功能教程

### 多点导航



### ROS开机启动



### 虚拟墙



### 语音交互



### 使用自定义的全局路径规划算法



### 多车仿真



### 搭建ROS仿真小车模型



### 目标检测



#### [实时目标检测(darknet_ros)](https://www.rt-thread.org/document/site/tutorial/smart-car/object-detection/object-detection/)

#### [Ros平台下基于face_recognition的人脸检测及识别](https://blog.csdn.net/qq_41658212/article/details/105399909)

#### [摄像头标定和opencv识别](https://zhuanlan.zhihu.com/p/179166753)




## [ROS书籍推荐](books.md)



## Git使用教程

### [高质量的Git中文教程](https://github.com/geeeeeeeeek/git-recipes)

### [Git小白教程](https://rogerdudler.github.io/git-guide/index.zh.html)

### [Git的奇技淫巧](https://github.com/521xueweihan/git-tips)




## 运动学模型

### [两轮差速结构](https://blog.csdn.net/iProphet/article/details/83661753)

### [麦克纳姆结构](https://blog.csdn.net/weixin_30627381/article/details/97069120)

### [阿克曼转向结构](https://blog.csdn.net/u013914471/article/details/82968608)




## 硬件资料

### 底层控制板


- #### STM32

- #### arduino

### 上层控制板


- #### 树莓派

- #### jetson nano










## 路径规划算法

基于图搜索的路径规划算法

基于采样的路径规划算法


## SLAM

### 激光slam

### 视觉slam




## 机器视觉



## 语音识别和控制

### ROS与语音交互教程 - 创客智造

&emsp;&emsp;教程链接 https://www.ncnynl.com/category/ros-voice/



### 古月居 ROS探索总结（十）—— 语音控制


&emsp;&emsp;教程链接  https://www.guyuehome.com/260



### 天之博特  中文ROS语音交互模块


&emsp;&emsp;教程链接 http://doc.tianbot.com/rosecho/1586400



### ROS小课堂 


&emsp;&emsp;视频链接 https://www.youku.com/profile/index/?spm=a2hbt.13141534.1_1.1&uid=UMTUzNzkwNTA1Ng==  （搜索语音交互）

![ROS小课堂-语音交互截图](https://gitee.com/wybros/Image/raw/master/img/ROS小课堂-语音交互截图.png)

### 小虎哥哥爱学习


&emsp;&emsp;课程链接 https://www.cnblogs.com/hiram-zhang/p/10421162.html



## [机器狗项目spotMicro](https://github.com/mike4192/spotMicro)

<img src="https://gitee.com/wybros/Image/raw/master/img/SpotMicroAI_complete_1.jpg" alt="SpotMicroAI" style="zoom:50%;" />





## 编程资料

### C/C++资料

### Python资料

### Linux资料


## 贡献者

这个项目的存在要感谢所有贡献者。 请给我们一个 🌟 Star 🌟支持我们。 谢谢。 并感谢所有支持者！ 🙏