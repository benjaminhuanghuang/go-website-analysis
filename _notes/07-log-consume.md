# 第7章 统计系统之日志消费
逐行批量的消费线上打点日志，实现四大Goroutine环节第一步，并且实现日志顺序进入带解析通道。对于线上流量凌晨期间的冷时间段，进行一定逻辑的等待循环处理。


## 7-1 统计分析模块逐行消费日志 (10:09)
