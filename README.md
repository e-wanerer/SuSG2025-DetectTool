# SuSG2025-DetectTool

项目名称：{操作系统异常信息检测工具} 
项目链接：{https://github.com/e-wanerer/SuSG2025-DetectTool.git}
导师信息：{宋凯，15071496396，songkai01@ieisystem.com}
难度：{中}
分类：{系统工具开发}
题目要求：
1）基础功能 
     支持检测以下系统异常状态：  
     1、OOM（内存不足）：检测系统因内存不足导致的进程终止。  
     2、Oops（内核错误）：检测内核崩溃或错误。  
     3、Panic（系统崩溃）：检测内核无法恢复的错误。  
     4、死锁（进程阻塞）：检测系统中出现的进程死锁。  
     5、reboot（系统重启）：检测非正常重启事件。  
     6、fs_exception（文件系统异常）：检测文件系统错误。
   进阶功能  
     1、实现异常状态的实时监控（如通过守护进程或定时任务）。  
     2、提供异常状态的统计和分类功能（如按异常类型、频率统计）。     
2）特征：
   1、工具需支持 Linux 系统。  
   2、提供命令行界面（CLI）和简单的配置文件（如 YAML/JSON）。  
   3、异常检测需支持关键词匹配和正则表达式匹配。  
3）预期目标：{预期学生完成的功能和性能列表、输出哪些文档，形式和数量的要求，源代码的要求等。本栏目可选，也可以合并到“题目要求”栏目。}
4）提交内容：  
  1、可运行的工具源码（含注释）。  
  2、工具的安装和使用文档。  
  3、至少 5 种异常状态的检测实现。  
  4、示例日志文件和测试用例。    
License：{GPL}
