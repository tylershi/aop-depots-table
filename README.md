"# aop-depots-table" 

基于AOP实现分库分表

分库分表策略
1. 一库多表
2. 多库一表
3. 多库多表

aop分库分表实现
1. 定义切面
2. 参数获取(路由字段解析)
3. hash 计算路由
4. 选择数据源(逻辑库映射实体库)
5. 选择数据表(逻辑表映射实体表)
6. sql执行
