# caidao-official-version
中国菜刀官方版本，拒绝黑吃黑，来路清晰

获取来源是官方的快照。

20111116版：http://web.archive.org/web/20121029144319/http://www.maicaidao.com:80/

20141213版：http://web.archive.org/web/20150417044256/http://www.maicaidao.com

20160622版：http://web.archive.org/web/20160624193117/http://www.maicaidao.com

MD5：
(chopper.exe)md5各版本校验码（仅exe主程序）: 

	20111116 => 5001ef50c7e869253a7c152a638eab8a
	20141213 => 4b4a956b9c7dc734f339fa05e4c2a990
	20160620 - ac86066ffd58779f4c0db5030574b0cb
	20160622 - acaf6564637ba97f73297b0096c2994c 	#修复了mysql乱码
	
	20160622配置文件caidao.conf - > 4ed9e48fcfc0119a0f47ea89db6cd6ab

更早：

	20111116 => 5001ef50c7e869253a7c152a638eab8a
		随GMT日期改变的动态密码，用法请注意看readme.txt
	20111022 => 7876d05ed4ee02967afc44a936186d2e
		Customize模式的C#服务端增加了数据库管理功能...
	20110811 => 854bb49a84ce784ad70da7fd356d4f49
		ASP.NET的上传部分Bug修复, 另写了一个Customize模式的C#服务端
	20110806 => 4c8bc36c41151170f701f755ef700916
		修复一些BUG
	20110710 => d89c5957a1dc72bb229be070635e19b2
		解决确认对话框返回值不正确的BUG。
	20110707 => ec66b85fba3a8b7d1a41910ae5239b24
		解决浏览器新标签页打开BUG。
	20110703 => 3a8140e8e124326388cb13e6d9d0d4b5
		配置里添了几个选项：
		默认终端程序路径设置示例：<SHELL>/bin/sh</SHELL>
		虚拟终端默认命令设置示例：<CMD>whoami</CMD>
		文件管理默认打开的目录设置示例：<CD>c:\windows\temp\</CD>
	20110630 => 7e6c415ca57e6ecaa6c61147a2549477
		数据库导入，自写脚本编码后再提交，修复浏览器小BUG，其它。
		网站开通自写脚本分享栏目，脚本编码规范可以看下载的示例。
	20110628 => 60b49098d099ad01c3d80a5f794d4ebd
		PHP连接MySQL加了个<L></L>选项，用来设置数据库的字符集;
		自写脚本可在浏览器里执行了，示例请看 Script/phpspy2011.ccc；
		解决目录文件过多时显示慢的问题；
		因为缓存库读取有了变化，本次更新后最好清空一下缓存库。
		可以下载ip.dat放到菜刀的目录,用来显示网站的国别。
		使用时的有问题可以给我发邮件。
	20100928 => c05d44dbe353525f492208d891b53875
		界面调整，修正了一些BUG，加了个ColdFusion版的示例服务端(仅文件管理和虚拟终端，MX 7及以下版本修改文件时间功能不可用)
	20100812 => 4398e87939edb8573c44592942dca503
		重大更新，从这个版本起，菜刀开放接口，支持所有的动态脚本，服务端可按需自定义。
		写了个jsp的服务端(文件管理/虚拟终端/数据库管理)，其它服务端可根据接口自个写！



