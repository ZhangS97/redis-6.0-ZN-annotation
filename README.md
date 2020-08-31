# 项目介绍
基于redis 6.0 的 加中文注释版redis

# redis文件架构介绍
|文件名|内容|
|-------|-------|
|``dict.h``、``dict.c``|字典数据结构的实现。|
|``adlist.c``、``adlist.h``|双端链表数据结构的实现。  |
|``ziplist.c``、``ziplist.h``| ZIPLIST 数据结构的实现，用于优化 LIST 类型。|
