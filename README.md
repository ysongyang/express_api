# 常用快递物流轨迹查询API对接工作日志

现在很多平台都可以查，为什么还要做这个没用的API呢，是的，确实很多平台都提供了。但是那些都是收费的，如果你是有钱的主完全可以忽略，有些时候，比如我们的电商平台有查询物流轨迹的需求，根据物流轨迹状态来更新订单状态，为了节省成本那就自己开鲁吧，对接各大物流公司的开放平台难度并不大。

>目前实现/正在对接的快递平台有：顺丰、百世快递、中通、韵达、申通、圆通、德邦。

快递API接口详情：https://api.zz1.com.cn/express/information

免费签发一个Token，这是一个测试Token与正式Token一样可用，只是限制了查询单量。

Token：Kbmu7ENFg3OQGMjgY15G7bqk3oB98ejY