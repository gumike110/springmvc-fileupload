﻿copy form fileupload.sys
springmvc实时进度条
=====================
fileupload.sys
=====================

1、框架采用spring mvc + mybatis  
2、初始化数据脚本fileupload.sys\src\main\resources\init.sql  
   数据库配置文件fileupload.sys\src\main\resources\jdbc.properties  
   log4j配置文件fileupload.sys\src\main\resources\log4j.properties  
   log4j采用分错误级别进行记录日志，比如错误日志只需要在fusys_error.log下找  
   spring mvc配置文件：总配置--fileupload.sys\src\main\resources\spring-root-context.xml,  
	数据库配置文件--fileupload.sys\src\main\resources\spring\spring-db-context.xml  
	mvc配置文件--fileupload.sys\src\main\resources\spring\spring-mvc-context.xml  
3、本地发布后就可以进行访问：  
    http://localhost:8080/fileupload.sys
