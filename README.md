# 基于Golang协程实现流量统计系统-慕课网实战

https://coding.imooc.com/class/192.html



- 第1章 课程介绍 试看
欢迎大家学习Go语言，本课程基于Go协程特性，实现企业级流量统计系统。关于Go语言，是一门朝气蓬勃富有战斗力的语言，它近些年的发展势头完全不亚于2012年前后的PHP语言，越来越多的Go语言爱好者、工程师。协程是Go最吸引眼球的特性，它将带你走进函数式编程的新世界。...

共 1 节 (14分钟) 收起列表

 1-1 课程概览 (13:58)试看

- 第2章 并发模型 试看
并发模型对于科班出生的同学并不陌生，在近些年的高级语言中，大量应用线程的并发能力做高并发应用，本章节将从并发模型开始，带你进入更轻量更高并发度的并发世界

共 3 节 (30分钟) 展开列表

- 第3章 Go的协程
Go语言天生自带协程：协程即Goroutine，但只学习Goroutine可远远不足以满足项目开发需要，本章介绍Go协程在做真实项目研发时所需要涉及的周边函数能力。以Sample代码为入手，让Go语言零基础的同学不掉队。

共 3 节 (23分钟) 展开列表

- 第4章 示例环境搭建
流量统计系统应用于成型互联网公司线上流量统计，本章节带领大家搭建一套含有一万多条数据的视频网站，整站嵌入用户信息上报JS，实时上报用户浏览情况，用于服务端统计分析。

共 4 节 (55分钟) 展开列表

- 第5章 Go批量生成日志
本章节通过一步步编写Go语言脚本，带大家实现一个可以自定义数量级的线上日志生成工具，用于模拟大量用户访问视频网站所产生的打点请求，生成数万行日志，用于后续统计分析系统消费。

共 3 节 (52分钟) 展开列表

第6章 统计系统框架构成
打点数据统计系统模块的骨架设计先行，将骨干Goroutine、Channel声明在先，一套清晰易懂的框架结构便于开发过程中专注于实现功能，在实际开发前就能摸清程序脉络，少走许多弯路。

共 2 节 (34分钟) 展开列表

第7章 统计系统之日志消费
逐行批量的消费线上打点日志，实现四大Goroutine环节第一步，并且实现日志顺序进入带解析通道。对于线上流量凌晨期间的冷时间段，进行一定逻辑的等待循环处理。

共 1 节 (11分钟) 展开列表

第8章 统计系统之批量解析
创建一组用于批量解析日志的Goroutine，是四大环节中并发度最高的环节，可以并行开展，相互之间不受牵制，分别扣取打点日志中关键信息，并构成自定义结构体，对上报信息翻译后放入待统计通道，给未来扩展能力提供了空间。...

共 1 节 (16分钟) 展开列表

第9章 统计系统之统计逻辑
最贴近业务需求的系统子模块，其中采用HyperLogLog能力实现UV天级去重，定义了用于存储数据所需的结构体后，对过往数据进行架构封装，投递至待存储通道，待存储器消费。

共 2 节 (30分钟) 展开列表

第10章 统计系统之存储器
无业务状态的通用存储Goroutine，将上游派发来的存储诉求逐个落实到存储系统中，并能扩展数据查询所需的时间维度数据，该环节对于存储知识要求较高，需要在不同的存储系统中选好最佳的抉择。

共 2 节 (21分钟) 展开列表

第11章 数据可视化
对于已落实到存储系统中的线上流量数据，本章节借助专业级的Dashboard脚手架Ant Design Pro，呈现美观的线上流量数据结果。彻底打通了用户侧系统的线上流量情况，将结果呈现在企业管理者、决策者的眼前。

共 1 节 (14分钟) 展开列表

第12章 企业级解决方案及课程总结
基于前面所涉及的内容，打通知识点，并且拆解企业级实现时，每个环节应当关注的点与系统方案的核心挑战剖析，抛砖引玉为学员提供更大的想象空间与成长空间

共 2 节 (15分钟) 展开列表