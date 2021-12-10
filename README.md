## 前言

Log4j2近日发现存在JNDI注入，从而存在远程代码执行漏洞的风险。作为java开发中近似于基础开发组件，其影响面是非常大的，甚至我们传入payload到其他语言的环境，只要这条数据能进到Log4j2也是会触发代码执行漏洞。

因为为了方便排查资产与影响面，这里公开部分我们已知受影响的其他组件，也非常欢迎大家一起提交mr。

## 已知影响组件

|                       |
| --------------------- |
| Apache Solr           |
| Apache Struts2        |
| Apache Druid          |
| Apache Flink          |
| flume                 |
| dubbo                 |
| Redis                 |
| logstash              |
| ElasticSearch         |
| kafka                 |
| ghidra                |
| 我的世界（Minecraft） |