# personnel_sys

#### 介绍
基于SpringBoot+Vue+Shiro+JWT+Redis+Mybatis-Plus的人事管理系统，人事管理的业务比较简单，主要是为了练习整合框架。

#### 软件架构
Bug自测


#### 安装教程

前端登录页：http://localhost:8081/login

接口文档：http://localhost:8080/swagger-ui.html

#### 使用说明

![image-20210422105358587](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105358587.png)

![image-20210422105414285](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105414285.png)

![image-20210422105443612](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105443612.png)

![image-20210422105501644](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105501644.png)

![image-20210422105510654](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105510654.png)

# 界面

简简单单的登录

![image-20210422105535459](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105535459.png)

简简单单的界面

![image-20210422105632434](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105632434.png)

日志

![image-20210422105730735](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105730735.png)

出勤

![image-20210422105745892](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105745892.png)

工资

![image-20210422105756883](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105756883.png)

奖惩

![image-20210422105821326](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105821326.png)

员工

![image-20210422105835899](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105835899.png)

培训

![image-20210422105847977](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105847977.png)

考核

![image-20210422105859438](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105859438.png)

变动

![image-20210422105909149](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105909149.png)

------

## 权限

用户

![image-20210422105945513](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422105945513.png)

![image-20210422110122911](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422110122911.png)

角色

![image-20210422110006177](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422110006177.png)

![image-20210422110153213](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422110153213.png)

权限

![image-20210422110024482](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422110024482.png)

![image-20210422110219574](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422110219574.png)

部门

![image-20210422110040770](https://gitee.com/MyClown/personnel_sys/raw/master/imgs/image-20210422110040770.png)

使用：

先从git上拉下来

![Snipaste_2021-11-19_15-56-51](https://gitee.com/MyClown/personnel_sys/raw/master/images/Snipaste_2021-11-19_15-56-51.png)

分别用编辑器打开![image-20211119165010357](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119165010357.png)

vue的控制台运行npm install

<s>每个页面的地址换成自己的，如果在一台服务器上可以Ctrl+R批量替换192.168.32.1为127.0.0.1；主要是每一个页面</s>（已经上传最新的修改后的）

![image-20211119165104596](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119165104596.png)

![image-20211119164947733](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119164947733.png)

运行npm run dev 或者直接点那个绿色的小三角，懂得都懂不懂得就命令吧

![image-20211119165244180](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119165244180.png)

控制台有前端地址

![image-20211119165329119](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119165329119.png)

后端导入：

下载完MVN的依赖查看一下别有报错

![image-20211119165356219](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119165356219.png)

创建数据库别忘了把地址和账号、密码换成自己的

![image-20211119165455394](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119165455394.png)

![image-20211119165505620](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119165505620.png)

导入sql

![image-20211119165519817](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119165519817.png)

![image-20211119165527808](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119165527808.png)

# 运行必须要redis

## 没有的可以下载个小P

![image-20211119165636038](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119165636038.png)

![image-20211119165644410](https://gitee.com/MyClown/personnel_sys/raw/master/images/image-20211119165644410.png)

然后就没有然后了。

<s>地址我就不改了比较懒</s>（已经上传最新的修改后的），当时没做封装要一个个换现在就费劲了。勿怪~