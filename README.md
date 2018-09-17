# EYEE-Spark-Training-Project

EYEE 员工培训项目 

== EYEE星火培训计划 ==
* [如何租用google cloud 免费搭建一个IPSecVPN Server，完全自由使用google学习最新的互联网技术。](https://github.com/tonycai/EYEE-Spark-Training-Project/blob/master/documents/Google%20Cloud%20%E6%90%AD%E5%BB%BAVPS.pdf)(1小时）
* 微服务化架构实践 - Docker （1，2，3）3个课时 
* Linux Command-Line Tools , bash shell & Vim  （1，2，3）3个课时
* [Using sqlmap for SQL Injection](https://github.com/tonycai/EYEE-Spark-Training-Project/wiki/Using-sqlmap-for-SQL-Injection) - Hacker (1h)
* 数据库设计规范及安全操作事项  2个课时
* 互联网后时代，如何抓住从信息网络到共识网络的机遇 - 区块链技术 （1，2，3）3个课时
* Artificial Intelligence （1，2，3）3个课时
* Big Data （1，2，3）3个课时
* [How to protect commercially confidential information](https://github.com/tonycai/EYEE-Spark-Training-Project/wiki/How-to-protect-commercially-confidential-information)

== Tech Concepts ==
* 一切衡量标准以用户为核心，电商本质是服务。
* 严谨客观真实的反映问题，尽可能用数据说话。
* 真诚热情的对待身边的人和事，帮助他人成功。
* 相信科技进步会让生活更美好，并且付诸行动。


== The Cardinal Rules ==
* 不允许出现图片外链，会存在潜在的风险。
* 批量修改超过100行数据，需要得到CTO的批准。
* 性能问题，核心接口响应时间要在1秒以内。
* 一次导出超过100条数据记录，需要得到CTO批准。
* 不批准连续超过两天的假期
* 添加定时任务，需要通过运维工程师上线流程，CC给技术主管和CTO。
* 技术底线：不丢数据，不写错数据，不删除数据。 怎么做到？全部数据做主从热备、持久化处理。先写入MySQL，然后再到缓存。当发生ES与MySQL数据冲突，以MySQL为主。
* 测试要先在我们自己的环境里重现Bug，确认是代码或者数据问题，然后再去找技术负责人解决问题。
* 每个人都要知道自己在什么位置，职权范围，未来可以期望的前景。如果不清楚的，要加强沟通。【NEW】
* 两张黄牌警告，一张红牌退场。【处罚措施】【NEW】
* 在正式环境下发版升级、维护，需要发邮件走CTO审批流程。【NEW】
* 数据表字段，因查询需要可以适当做冗余，同时可以允许有5分钟滞后更新，有24小时后纠错补偿机制。【NEW】
