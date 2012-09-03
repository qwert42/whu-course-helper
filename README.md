## 帮助使用whu选课网站的本地脚本 ##

目前版本支持导出你的课程，生成一个html的课表，并且可以同步到你的Google日历
本项目在GPL许可证下发布，你可以在<http://www.gnu.org/copyleft/gpl.html>找到一个该许可证的副本

#### TODO ####

1. 支持更多学校
2. 打包为exe


#### 开发、测试环境 ####

*   2012/9/3T14:14
	更新为python2.7, pycharm2.5.2

*   earlier
	win7，python2.6, pycharm2.0.2

#### 依赖的库 ####

*   2012/9/3T14:14
	gdata更新为2.0.17

*   earlier
	BeautifulSoup3.2 许可证为Simplified BSD License
	gdata-2.0.16 许可证为Apache License 2.0



#### 日志 ####

*   2012/9/3T14:14
	0.0.9a
	项目修订 - 更改了开学日期，修复了少量bug，更新了一下gdata库的使用

*   2012/3/4T12:48
	0.0.9
	项目重构 - 使得自定义课程能用于更多的学校，具体请查看doc下的相关文档（关于自定义课程的文档还没开始写）
	学校扩展指南v0完成，待修订

*   2012/3/3T15:31
	0.0.8
	项目重构 - 使得Google日历能够应用于更多的学校，具体请查看doc下的相关文档（Google日历的相关文档已完成）

*   2012/2/23T13:39
	0.0.7d
	bug修正 - 修正了CourseSchedule的一处正则错误

*   2012/2/23T12:51
	0.0.7c
	增加了verbose回显

*   2012/2/23T12:44
	0.0.7b
	bug修正 - 对GoogleCalendarAdapter导入的课程进行了判重

*   2012/2/23T12:06
	0.0.7a
	bug修正 - 现在载入课程时会判重

*   2012/2/22T23:26
	0.0.7
	1.你现在可以创建自定义课程了，
	2.现在有更多的设置选项了，具体请查看CONFIG_SAMPLE

*   2012/2/22T18:00
	0.0.6
	现在可以通过config自定义一些程序行为了，请查看CONFIG_SAMPLE

*   2012/2/21T10:34
	0.0.5a
	1. 将repo移到了whu-course-helper
	2. 自动选择命令行编码

*   2012/2/20T22:19
	0.0.5
	课程现在可以被序列化（保存在本地）了，当然也可以反序列化（从文件中读出）

*   2012/2/19T11:22
	0.0.4a
	bug修正 - 之前搞忘了课程开始周这个参数了= =

*   2012/2/19T00:43
	0.0.4
	可以同步课表到Google日历了

*   2012/2/13
	0.0.3
	可以输出课表到html文件了

*   earlier
	0.0.2
	支持抓取课程了

*   earlier
	0.0.1
	在github上共享

*   earlier
	0.0.0
	创建了项目原型

e-mail: chsc4698@gmail.com
all rights reserved

