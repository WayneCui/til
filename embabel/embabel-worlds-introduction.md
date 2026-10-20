
[A New Layer for a New Client: Introducing Embabel Worlds](https://medium.com/@springrod/a-new-layer-for-a-new-client-introducing-embabel-worlds-616ccde93533)


# Notes | LLM 是新浏览器，「上下文层」是新中间件

Spring 之父 Rod Johnson 发布 Embabel Worlds。

# 三个速读观察

1. AI 的价值不只在“系统内部”，更在“系统之上”

一个架构问题: AI 是加在现有系统内部，还是加在现有系统之上？

显然是后者。

90 年代浏览器成为新客户端，催生了中间件；如今 LLM 成为新客户端，催生的是上下文层。

2. MCP vs code mode

Code Agent 的巨大成功带来的启发：

在模型之上，代码天然提供了上下文层，因为模型知道如何高效地写脚本、写代码。

那么，coding 领域之外的领域呢？

3. Script your business

Embabel Worlds 让模型对业务直接写脚本（Cypher + TypeScript，沙箱执行）

例如，客服工单按照「业务受损 × 当前情绪」两个由模型判定的标签进行排序。


# 存疑

尚且不知这款产品如何支持 Cypher 查询非结构化的数据。疑似与祝威廉的 InfiniSynapse 类似，后者采用的是 SQL 。有时间对比一下。

MCP 不应该被一棒子打死。内部系统如何暴露给 Agent？

（速读笔记，可能有误，欢迎指正。）
