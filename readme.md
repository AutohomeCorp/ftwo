# 简介
ftwo 是汽车之家经销商部门实施的一套页面质量体系。包含前端监控 SDK 、页面性能分析工具和站点评分三部分。支持采集页面异常、性能和行为数据，提供优化页面性能方案，输出站点评分。为前端同学持续提升页面质量，保驾护航。

[卓越工程生产力大会-分享 ppt ](res/%E6%B1%BD%E8%BD%A6%E4%B9%8B%E5%AE%B6%E9%A1%B5%E9%9D%A2%E8%B4%A8%E9%87%8F%E4%BD%93%E7%B3%BB%E5%BB%BA%E8%AE%BE%E4%B8%8E%E5%AE%9E%E8%B7%B5.pdf)

我们将逐步开源整套方案，**敬请关注！**

# 开源计划

模块 | 介绍  | 时间
---|--- |---
ftwo-sdk | 采集页面异常、性能、行为等数据的SDK | 2022-07-31前
ftwo-es  | es上存储数据的索引模板        | 2022-07-31前 
ftwo-receiver  | 数据接收，含异步接收、sourcemap解码、异常上下文抓取、UA解析、提交至kafka等功能 | 2022-10-31前
ftwo-flink     | 数据流转，将kafka数据通过flink批量提交到es                                  | 2022-10-31前
其余     | 待定                                  | 待定