# FreeSQL
SparkSQL执行HiveQL文件

## 

## 封装Oozie调度SparkSQL解析HiveQL文件可重用jar包
处理过程：
变换key=value为Map(key,value)
转换key为$key
去除SQL语句中的注释（--开头）
去除SQL语句中的大括号{}
替换SQL语句中的参数
去除分号
执行SQL