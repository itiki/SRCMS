# 欢迎使用SRCMS V2社区开发版 ![codebeat badge](https://codebeat.co/badges/67e58b6d-bc89-4f22-ba8f-7668a9c15c5a)

**SRCMS** 是一款安全应急响应与缺陷管理软件，致力于为大、中、小企业和组织提供“最敏捷、安全和美观的安全应急响应中心的建站解决方案，帮助企业建立属于自己的安全应急响应中心和体系”。有了SRCMS，您就可以像使用Discuz!搭建论坛一样容易，为您的企业建立安全应急响应中心平台。

> * **项目维护:** Martin Zhou
> * **官网：**http://www.srcms.xyz
> * **最后更新日期：**2017-02-07
> * **演示站点：**http://www.srcms.xyz/demo/index.php


##授权说明
任何人在未取得SRCMS开发者正式书面授权的情况下，不得将SRCMS项目源代码或二次开发过的源代码用作商业出售用途，否则将保留追究其法律责任的权利。 

##免责说明
SRCMS仅为建站软件，任何使用本建站程序搭建的网站其运营的内容所产生的法律纠纷与本项目以及本人无关。

## SRCMS V2企业版
目前开源的SRCMS V2社区开发版仅包含核心功能，如您需要体验更为完善的全功能企业版(含数据中心和缺陷管理、漏洞维基等高级模块)，可通过以下地址申请购买： 
https://wj.qq.com/s/1063767/129c

##运行配置说明
* 第一步：部署运行环境（PHP版本建议在5.3-5.6，5.6版本可能存在不兼容的情况）
* 第二步：脚本运行后程序和环境便已经释放完毕，直接访问对应链接，登录后台完成站点的配置（默认前台账号:user/useruser 后台账号:admin/admin）
* 第三步：进入\Application\Common\Conf\db.php，配置数据库链接
* 第四步：进入\Application\User\Controller\PostController.class.php，第69行配置新增漏洞报告提醒邮箱
* 第五步：配置完成

##版本更新日志

#####2017-02-07（建议等级：选择更新）
* **新增** 前台新增漏洞报告提示
* **新增** 前台积分记录
* **优化** 后台页面打开速度

#####2017-02-03（建议等级：推荐更新）
* **新增** SRCMS V2开发版

##BUG提交说明
如果您在使用本框架或是二次开发中发现任何SRCMS的问题，欢迎迎通过Github的issue功能将问题反馈，Issue功能能够很好的帮助我们定位和跟踪问题的修复情况。 

##致谢
在开发过程中，SRCMS得益于广大开源项目和开发者们的帮助和支持,在此向下面的开发者们致谢：
* [ThinkPHP](http://www.thinkphp.cn/)
* mramydnei
* Del技术菜鸟
* Blast
* Ivan
* 藏形匿影(挖财网)

&copy;<a href="https://github.com/CNSISMO" target="_blank">CNSISMO</a> 2016 - 2017
