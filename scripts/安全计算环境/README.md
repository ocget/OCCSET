## 等级保护基线检查工具



* Hp-Unix
	> * 笔记而已。
* Linux
	> * capos.sh 	        红帽系linxu版本测评使用,兼容6.x，7.x版本，兼容Oracle, Mysql,开始支持对中间件的检测，后面一点点的完善。并且添加了logo，也算注入灵魂了。
	> * suse11.sh			Suse linux 11.X 版本测评使用。
	> * secure_config.sh 	红帽系linux 口令策略，登录失败策略，登录超时整改脚本。
* Windows
    > * 该小工具使用golang语言编写，包含多个版本，可生成 txt文档和word测评结果文档，可在测windows终端时使用，存在隐藏未解决的bug。项目源码：https://github.com/lis912/CapOS,  建议使用v1.3.2版,这版去掉了没有用的doc文档输出,添加了一些提示信息,直接生成TXT到当前目录.
* Mysql
	> * mysql.sql			5.0以上版本适用，使用方法在该文件开头。		
* Oracle
	> * oracle_10g.sql……	使用方法在文件开头有说明。
* Sybase
	> * 笔记而已。
