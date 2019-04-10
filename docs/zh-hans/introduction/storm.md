# 边缘计算管理平台 Storm


## 简介

EMQ X Storm （以下简称 Storm 平台）是一个面向 EMQ X Edge 边缘消息服务器的管理平台，用于解决如下问题：

1. Edge 边缘消息服务器实际部署数量较多、位置分散且服务器所处空间环境相对复杂，难以开展运维管理工作如获取监控服务器状态与运行指标、变更相关功能配置、固件升级；
2. 边缘节点上的设备接入、消息路由数据处理、数据透传等计算规则可能需要随着业务运营进行变更，需要一个规则管理与派发平台实现计算规则的编辑、版本控制、下发等操作。

EMQ X Storm 将边缘节点的监控管理中心化，通过 Web 界面及管理监控 REST API 支撑以上需求。




**在线运营:** [https://storm.emqx.io](https://storm.emqx.io)

**Github（暂未开源，用于 Issues 反馈、需求发布）:** [https://github.com/emqx/storm](https://github.com/emqx/storm)



![storm_spec](../_assets/storm_spec.png)


