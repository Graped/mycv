# 丁超越的简历
# 个人信息

 - 丁超越/男/1990 
 - 本科/安徽农业大学 
 - 硕士/中国科技大学
 - 工作年限：5年
 - 微信/QQ：56171014
 - 电话: 18895660822、18601611630
 - Github：[https://github.com/Graped](https://github.com/Graped)
 - 技术博客：[http://www.grapedlinux.cn/](http://www.grapedlinux.cn/)

 - 期望职位：Linux运维工程师, Linux运维开发工程师

# 技能清单

## 日常技能
> 以下均为我工作中经常使用到的技能
- 搭建 RedHat、CentOS 下各种服务（如 Samba、FTP、NFS 、DNS 等）；
- redhat/centos 系统的日常管理；
- Mysql 的数据冷热备份与恢复、mysql 调优、主从复制以及读写分离的实现、缓解高并发时主数据库的读写压力，并提升读写速度。
- Web 服务设计、搭建、配置，性能优化，安全控制。LAMP、LNMP、Nginx 性能调优，内核参数调优；
- 配置 Apache 的日志管理、用户认证、静态缓存、防盗链、访问控制、域名跳转等功能；
- 配置 Nginx 的常规web 服务、反向代理、作缓存服务、动静态分离、负载均衡等功能；
- 用 squid 给网站配置缓存服务器，配置缓存对象和缓存策略、利用 ACL 对端口、IP、域名、HTTP 请求等对象进行访问控制。
-  LVS/nginx+heartbeat/keepalived+apache+mysql，前端使用更高性能的 LVS 实现负载均衡，使用 keepalived 做 HA 集群实现保证网站的稳定性。后端的 mysql 主从
- 数据库采用mysqlproxy 实现读写分离，降低主库的负载。
- 编写 nagios/zabbix 等监控工具的 shell 脚本，监控整个系统以及关键服务的运行，及时发现安全隐患和性能瓶颈，实现邮箱和短信报警。
- 制定安全规范，通过权限管理、认证机制、数据备份、，保证服务器数据的安全。
- 利用系统管理工具以及日志分析对服务器的软硬件故障进行定位解决；
- 熟悉 redhat、centOS 等 linux 系统，能够对其进行光盘安装和网络无人职守安装、系统优化、故障排除、系统安全加固、光盘引导进行灾难性恢复；
- 熟悉 LAMP、LNMP，nginx+tomcat 等 web 服务架构，能够搭建、配置、调优；
- 熟练掌握 LVS/nginx 负载均衡集群,对于 LVS 的四种 NAT,DR，tun,fullnat 模式原理有一定研究，熟悉负载均衡常用算法。
- 熟练掌握高可用集群 heatbeat 和 keepalive 原理以及相关配置。
- 熟悉 mysql 数据库，对 mysql 数据库，能够熟练的安装、故障排除、调优、主从复制，熟悉 Redis 数据库的存储原理、主从复制、持久化、高速缓存。
- 熟悉掌握 squid 缓存服务器、DNS 域名解析服务、NFS 文件系统共享、ftp 服务、postfix 邮箱等常用服务的原理、搭建、配置。
- 熟悉 Shell Script 编程、awk、sed、grep 等脚本辅助工具进行日常系统管理，如监控脚本的制定、自定义任务执行、应用的安装配置等。
- 熟悉docker，私有化配置。

## 其他技能
- python自主学习中
- 编辑器/IDE: VIM/Pycharm
- 版本管理、文档和自动化部署工具：Git/Markdown/Ansible
- 公有云：熟悉阿里云各个产品, 并了解其使用场景, 其他云厂商也有了解


# 工作经历

## **联想集团**   (2017年4月-至今）
> 联想云G15 高级Linux运维工程师
### 联想云非结构化数据管理平台

联想云非结构化数据管理平台是一个集中管理非结构化数据的统一管理系统, 它的功能有以下几点:

* 资源监控，采用控软件 Nagios+Zabbix
* 协同办公、移动办公
* 文档管理
* 在线预览office文档，视频，CAD图纸等

我在工作中的职责:

* 实施部署联想私有云非结构化管理平台V4.0、V5.0及其附属增值模块系统
* 保障私有云、混合云和专有云架构下的网盘平台、预览平台、系统编辑平台业务运行正常
* 根据每台服务器的具体状况和需求制定模板进行监控实时报警
* 日常工作脚本的编写于优化工作，例如：网盘备份脚本，系统运行情况call-home监控报警脚本、系统参数、中间件参数优化脚本等
* 日常工作难点、重点的破冰
* 以及新员工入职的培训、华东区运维售后团队的带领


### 其他职责

* 协助业务部门规范化标准和规范，提升沟通效率
* 负责公司公有云阿里云及IDC的业务、系统、网络、硬件、基础服务的建设及运维工作
  
## 巨子科技有限公司 (2014年8月-2017年4月)
> linux运维工程师

### 论坛搭建

* 搭建是一个基于LNMP的论坛，主要用于业务人员日常图片的回收工作
* 我在这个项目中负责LNMP和Discuz的部署、站点日志定义及切割保存， 目录访问控制，网站后台限制，防盗链，图片缓存，等安全防范措施以及cacti监控配置
* 主要使用到的技术栈是nginx、mysql、php的部署，nginx的使用等
* 通过这个项目, 我对nginx、等知识有了整体上的理解


### 负载均衡配置

* 我在这个项目中负责负载均衡的配置工作
* 整个项目总共使用了 4 台服务器，采用 LVS 的 DR 模式。配置 keepalived
实现两台调度器的双机热备，避免单点故障引起的服务中断。使用 LVS 的轮询调度（RR）算法，实现两台 web 服务器的负载均衡。上线了一套监控系统 zabbix。主要监控各个服务器的内存使用率、磁盘空间大小、CPU 负载、网卡流量、各服务端口的运行情况，实现在服务器出现异常的时候，监控系统就会报警，第一时间收到邮件提醒， 及时处理故障。

## 南京Simbaa (2013年7月-2014年7月)

### 虚拟化IDC运维

* 公司服务器运维项目，项目上有1000台左右服务器需要维护，包括日常检查，数据报表展示，基础服务的安装配置等等，通过这 个项目，最大的收获是认识到运维自动化的重要性，经过这个项目，自己的shell编写能力大大提高, 并初步了解到了python;
* 监控采用的是nagios系统, 加上自己编写的shell脚本
* 由于是在实习期，在工作中逐渐意识到自己的不足之处

## 安徽农业大学 (2011年7月-2013年7月)

### 校内网

* 搭建这个校园校内网的目的是方便大家交友娱乐，提供开源网盘onecloud、校园网夜间禁止上网等服务.
* 用户大概有1万左右，从购买硬件到安装操作系统，从安装LNMP，到搭建Discuz，都是我们两个人来完成.
* 经过这个小小的项目，我熟练掌握了linux基础知识，以及TCP/IP相关的知识.
* 同时也培养了一定的问题排错能力和团队协作能力,另外我还意识到兴趣是最好的老师.

## 技术文章

- [干货 | XtraBackup不停机不锁表搭建MySQL主从同步实践](http://www.grapedlinux.cn/2017/03/23/17032302/)
- [工具 | 网盘单机数据库&数据块冷备](https://box.lenovo.com/l/951N0R)



## 自我总结

* 热爱开源, 热爱技术, 擅长使用最合适的技术解决企业的问题, 为企业创造价值;
* 我是一个勇于承担责任的人, 对工作负责, 对自己负责; 
* 具有分析大型应用系统架构并进行改进的能力，拥有快速排查系统瓶颈的能力；
* 有较强的沟通及协调能力，学习能力强，做事沉稳细致、具有良好文档编写和文字表达能力；
* 具有扎实的基础，熟练掌握 Linux 技能。
* 遇事冷静，碰到问题有良好清晰排查和解决思路。
* 抗压能力较强，能较好的应对并适应各种环境变量
* 动手和学习能力强，针对一些新问题新技术，尤其是运维业务及相关领域，会主动探索解决方案及创新方式
* 具有良好的团队精神及沟通协调能力
* 执行力强，工作认真严谨，具有强烈的上进心和责任心，目前正在自学 Python 语言，期望在 1-2 年能达成运维开发工程师的职业规划




