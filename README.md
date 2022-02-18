## Kms项目介绍



**项目背景**



了解到部分单位对于钥匙管理的还是停留在人工登记的层次，并且需要消耗大量的纸张进行记录，也会出现不登记钥匙就随意拿取钥匙的现象，钥匙的安全性也不能得到保证。所以就有了kms的诞生以帮助他们解决上面所遇到的问题。



**面向群体**



公司、单位对钥匙进行集中智能化管理的团体。



**核心思想**



自动化：



利用软硬件结合的方法，用户只需要在手机上预定会议室，系统会主动推送领取钥匙、归还钥匙的消息提醒，让用户把时间利用的更充分。



易管理：



所有钥匙做到统一管理，脱离人工管理钥匙，实现用户随时可以有钥匙使用，预约会议室后即可领取相应的钥匙。减少了钥匙丢失的可能性。



智能化：



如果用户在发送日程的时候，没有一个固定的会议室，那我们系统将会推送一个最符合用户的会议室。



**产品亮点**



１、界面直观



通过消息卡片的形式提醒用户及时领取、归还钥匙，并在会议开始和结束前对用户进行消息提醒。提高用户的时间管理能力。



２、高效性



为了减少人员的负担，大量的工作被交给了客户端来实现，以减少人员管理钥匙的压力，保证工作效率的提高。



**产品框架**



WCF、JQuery



**实际展示（截图或视频）**



1、给用户推送周报



![给用户推送周报](https://img-blog.csdnimg.cn/dcc316da552340b9b4799e8d878f7a05.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA546L5qKm5p2wLg==,size_13,color_FFFFFF,t_70,g_se,x_16#pic_center))



每周为用户推送用户的使用情况，并在周报中体现出用户使用的次数、时间段和时间。



2、给用户推送会议室



![给用户推送会议室](https://img-blog.csdnimg.cn/5319937917224f22a63b4312a448690a.png#pic_center))



根据会议内容以及时长为用户推送可能符合用户需要的会议室，如果用户认为可以使用这个会议室，那么可以申请，如果不想使用这个会议室，直接拒绝，还会给用户推送下一个。



3、![提醒用户领取钥匙](https://img-blog.csdnimg.cn/22bd8ccb063542d28a0c568c8a85e5e7.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA546L5qKm5p2wLg==,size_19,color_FFFFFF,t_70,g_se,x_16#pic_center)



当用户申请完会议室后，在会议前30分钟会提醒用户领取钥匙。



4、提醒用户归还钥匙



![提醒用户归还钥匙](https://img-blog.csdnimg.cn/c83ff8b167444626b09e97303889d329.png#pic_center)



在会议结束前10分钟，会提醒用户归还钥匙，也是提醒用户会议室使用快要到期，注意时间把控。



5、提醒用户把控时间



当用户超出会议时长时，会有相应的积分扣除，提醒用户下次会议注意把控时长。



**联系我们：**



**手机号：18730628608****（微信同步：武先生）**



**邮箱：w2402290237@163.com**



----



## 应用场景





### 介绍



      Kms主要是用于会议室钥匙的管理，但我们有使用会议室的需求的时候就需要通过发送日程来完成，借用会议室并且拿到会议室对应的钥匙。



### 时间



       使用会议室的具体时间，可以提前发送日程进行会议室的预约也可以随时使用会议室随时发送日程。比如说预约会议室，今天是周二，我想周三上午8:00-9:00使用会议室，那在发送日程的时候选择周三对应的日期选择8:00-9:00就完成了会议室的预约。



![时间](https://img-blog.csdnimg.cn/5393d55fc2484014bcbe12f0dad951bb.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA546L5qKm5p2wLg==,size_20,color_FFFFFF,t_70,g_se,x_16#pic_center)



### 地点



       每个会议室可能存在基础设备的不同，比如有的会议室有LED大屏，有的会议室有白板。可以根据自己的会议需求来选择对应的会议室。



![地点](https://img-blog.csdnimg.cn/030cf6f53af34ed7afbba18d7aedaabe.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA546L5qKm5p2wLg==,size_20,color_FFFFFF,t_70,g_se,x_16#pic_center)



### 人物



       会议的组织人，可以添加上会议的参与人。



![人物](https://img-blog.csdnimg.cn/457501732e2a41ff90bbecb5f412f1c9.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA546L5qKm5p2wLg==,size_20,color_FFFFFF,t_70,g_se,x_16#pic_center)



### 行为



1.  通过组织会议使用会议室

2.  通过技术分享使用会议室

3.  通过带人参观使用会议室

4.  。。。。。。



----

## 项目部署流程



第一步，钉钉后台创建机器人应用以及h5应用



第二步，配置机器人应用以及h5应用的应用信息



1.配置机器人消息接收地址



![配置机器人消息接收地址](https://img-blog.csdnimg.cn/e2494bf17b7b4241b15ed112cdd7aed2.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA546L5qKm5p2wLg==,size_20,color_FFFFFF,t_70,g_se,x_16#pic_center)



机器人权限



![机器人权限](https://img-blog.csdnimg.cn/103b354619694d3abd5f762efc289eb3.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA546L5qKm5p2wLg==,size_20,color_FFFFFF,t_70,g_se,x_16#pic_center)



2.h5应用信息配置



这是两个应用要配置的信息，由于这系统是在钉钉的平台上进行开发的，需要钉钉的很多功能，接下来一一列出所需的接口以及注意事项



接口部分：



[钉钉h5应用配置事件订阅接口文档](https://open.dingtalk.com/document/org/configure-event-subcription)



![钉钉h5应用配置事件订阅接口文档](https://img-blog.csdnimg.cn/d0e603d9709b48e487a3c938193fecb7.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA546L5qKm5p2wLg==,size_20,color_FFFFFF,t_70,g_se,x_16#pic_center)



[发送钉钉互动卡片接口](https://open.dingtalk.com/document/robots/send-interactive-dynamic-cards)



这里要说明一下，本系统使用的钉钉卡片实现的用户互动，所以需要回调，后面会展示回调的部分。



[钉钉互动卡片回调地址注册接口](https://open.dingtalk.com/document/robots/register-an-interaction-card-callback-address)



[更新钉钉互动卡片接口文档](https://open.dingtalk.com/document/robots/update-dingtalk-interactive-cards)



[钉钉卡片搭建平台](https://open.dingtalk.com/document/resourcedownload/card-building-platform)



我们常用的卡片是自己通过这个平台设计的



接下来是在程序代码部分的注意事项了：



![程序代码部分注意事项](https://img-blog.csdnimg.cn/9bdeb4f26fa84f8ea34ebd845f8d5291.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA546L5qKm5p2wLg==,size_20,color_FFFFFF,t_70,g_se,x_16#pic_center)



这个系统是使用的.net开发的，通过把这个webapi服务通过iis发布就可以接可以把这些api接口放到钉钉后台应用里面，这就是前面说钉钉机器人和h5应用放的两个地址都是源于这个，但是要注意了一定要是公网可访问的接口才行，因为是钉钉那边调用你的接口才行。



![公网可访问接口](https://img-blog.csdnimg.cn/604aaaf915ab4a08a7e45109bc208316.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA546L5qKm5p2wLg==,size_20,color_FFFFFF,t_70,g_se,x_16#pic_center)



这个是使用钉钉接口需要的信息，把这个更换成自己的钉钉后台应用的信息即可。



以上这些是和钉钉交互的信息，下面介绍第三步的后台管理的配置。



第三步，配置后台管理服务



我们程序后端的逻辑处理在这里是通过wcf服务实现的，通过webapi服务这边引用服务，这样就实现了接口和后端分离了，这个也是通过iis发布即可。



第四步， 数据库配置



由于我们这个系统是配合着硬件来使用的，而硬件具有限制性，就需要有信息的记录这样才能做到钥匙管理而不会出差错，通过数据库存储每一次开锁以及钥匙领取的信息。





CREATE TABLE \`t\_manager\_record\` (



\`id\` int(11) NOT NULL AUTO_INCREMENT COMMENT '自增',



\`manager_name\` varchar(10) NOT NULL COMMENT '管理员姓名',



\`key_name\` varchar(10) NOT NULL COMMENT '领取钥匙名称',



\`user_id\` varchar(30) NOT NULL COMMENT '用户钉钉ID',



\`get_time\` datetime DEFAULT NULL COMMENT '领取时间',



\`is\_return\_key\` tinyint(2) DEFAULT NULL COMMENT '是否归还',



\`is_cancel\` tinyint(2) DEFAULT NULL COMMENT '卡片是否作废',



\`create_time\` datetime NOT NULL COMMENT '创建时间',



\`update_time\` datetime DEFAULT NULL COMMENT '修改时间',



\`get\_out\_track_id\` varchar(40) NOT NULL COMMENT '领取钥匙卡片消息ID',



\`return\_out\_track_id\` varchar(40) DEFAULT NULL COMMENT '归还钥匙卡片消息ID',



PRIMARY KEY (\`id\`)



) ENGINE=InnoDB AUTO_INCREMENT=37 DEFAULT CHARSET=utf8 COMMENT='管理员领取钥匙记录表';



CREATE TABLE \`t_calendar\` (



\`id\` int(11) NOT NULL AUTO_INCREMENT COMMENT ' 自增id',



\`calendar_id\` text NOT NULL COMMENT '日程ID',



\`content\` varchar(100) NOT NULL COMMENT '内容',



\`start_time\` datetime NOT NULL COMMENT '会议开始时间',



\`end_time\` datetime NOT NULL COMMENT '会议结束时间',



\`return_time\` datetime DEFAULT NULL COMMENT '钥匙返回时间',



\`room_name\` varchar(10) DEFAULT NULL COMMENT '房间ID',



\`attend_count\` varchar(100) NOT NULL COMMENT '参会人',



\`organizer\` varchar(10) NOT NULL COMMENT '组织人',



\`approver\` varchar(30) DEFAULT NULL COMMENT '审批人',



\`send_people\` varchar(30) DEFAULT NULL COMMENT '抄送人',



\`organizer_id\` varchar(30) NOT NULL COMMENT '组织者dingid',



\`create_time\` datetime DEFAULT NULL COMMENT '创建时间',



\`update_time\` datetime DEFAULT NULL COMMENT '更新时间',



\`is_start\` tinyint(2) DEFAULT NULL COMMENT '会议开始时间的状态',



\`is_end\` tinyint(2) DEFAULT NULL COMMENT '会议结束时间的状态',



\`out\_track\_id\` varchar(40) DEFAULT NULL COMMENT '唯一标识一条卡片消息的外部编码',



PRIMARY KEY (\`id\`)



) ENGINE=InnoDB AUTO_INCREMENT=543 DEFAULT CHARSET=utf8 COMMENT='日程信息表';



CREATE TABLE \`t_room\` (



\`id\` int(11) NOT NULL AUTO_INCREMENT COMMENT '自增ID',



\`lock_number\` varchar(2) NOT NULL COMMENT '锁编号',



\`room_name\` varchar(10) NOT NULL COMMENT '教室名称',



\`lock_state\` varchar(12) NOT NULL COMMENT '锁的状态',



\`front_min\` int(11) NOT NULL COMMENT '开锁前多少分钟可以取钥匙',



\`min\_use\_number\` int(11) DEFAULT NULL COMMENT '教室最少使用人数',



\`create_time\` datetime DEFAULT NULL COMMENT '创建时间',



\`update_time\` datetime DEFAULT NULL COMMENT '更新时间',



PRIMARY KEY (\`id\`)



) ENGINE=InnoDB AUTO_INCREMENT=9 DEFAULT CHARSET=utf8 COMMENT='房间信息表';



CREATE TABLE \`t_basicdata\` (



\`id\` int(11) NOT NULL AUTO_INCREMENT COMMENT '主键id',



\`room_name\` varchar(10) DEFAULT NULL COMMENT '教室名称',



\`min\_use\_number\` int(4) DEFAULT NULL COMMENT '至少使用人数',



\`before\_take\_key\` int(4) DEFAULT NULL COMMENT '会议开始前*分钟取钥匙',



\`after\_return\_key\` int(4) DEFAULT NULL COMMENT '会议结束前*分钟还钥匙',



\`upper_time\` int(11) DEFAULT NULL COMMENT '会议室使用时间上限',



\`lower_time\` int(11) DEFAULT NULL COMMENT '会议室使用时间下限',



\`approver\` varchar(10) DEFAULT NULL COMMENT '审批人',



\`create_time\` datetime DEFAULT NULL COMMENT '创建时间',



\`update_time\` datetime DEFAULT NULL COMMENT '更新时间',



PRIMARY KEY (\`id\`) USING BTREE



) ENGINE=InnoDB AUTO\_INCREMENT=8 DEFAULT CHARSET=utf8 ROW\_FORMAT=COMPACT COMMENT='基本数据配置表';
