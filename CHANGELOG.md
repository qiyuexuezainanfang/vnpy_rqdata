# 2.9.56.1版本
1. 增加RqdataGateway行情接口，方便跨市场仿真测试

# 2.9.56.0版本
1. 使用zoneinfo替换pytz时区功能

# 2.9.48.2版本
1. 完善函数和变量类型声明
2. 修复rqdatac返回缺失数据为NaN导致的解析问题
3. 使用itertuples代替iterrows来加快读取速度

# 2.9.44.1版本
1. 放宽rqdatac的版本依赖为大于等于指定版本

# 2.9.44.0版本

1. 升级支持rqdatac的2.9.44版本
2. 禁用rqdatac的自动插件加载