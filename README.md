# yc-udid
UUID for yc

## UUID

> 通用唯一识别码 (Universally Unique Identifier)

#### UUID 组合：

1. 当前日期和时间，UUID的第一个部分与时间有关，如果你在生成一个UUID之后，过几秒又生成一个UUID，则第一个部分不同，其余相同。
2. 时钟序列
3. 全局唯一的IEEE机器识别号，如果有网卡，从网卡MAC地址获得，没有网卡以其他方式获得

更多[参考百度百科](http://baike.baidu.com/view/1052579.htm)