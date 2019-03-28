# 接入前准备工作

易观方舟支持全端数据接入：

* **客户端**

  [Android SDK](../sdk/sdk-android/)

  [iOS SDK](../sdk/sdk-ios.md)

  [JS SDK](../sdk/sdk-js.md)

  [小程序 SDK](../sdk/sdk-wx.md)

  [Hybrid Android SDK](../sdk/hybrid-sdk/sdk-hybrid-android.md)

  [Hybrid iOS SDK](../sdk/hybrid-sdk/sdk-hybrid-ios.md)

* **服务端**

  [Java SDK](../sdk/sdk-java.md)

* **工具导入**

  [历史数据导入](../tool-import.md)

## 不同接入方式的差异

|  | 适用场景 | 埋点方式 |
| :--- | :--- | :--- |
| 客户端埋点 | 更适合采集用户前端行为数据，简单易用 | 代码埋点/可视化埋点 |
| 服务端埋点 | 更适合采集业务相关数据，因为和业务调用同步，会更进准，同时安全性更高 | 代码埋点 |
| 工具导入 | 生成符合格式的数据直接导入，通常使用于已经存在历史数据，并希望导入方舟来分析 | 工具导入 |

## 接入前建议阅读

1. [数据模型](integration-data-model.md)，以便于更充分的了解数据的扩展性；
2. [数据格式](integration-data-type.md)，以便于更准确的集成SDK，符合分析需要；
3. [预置事件和属性](integration-default-data.md)，以便于确定哪些是系统默认采集，无需额外工作量就可以分析，哪些如果有分析需求需要上报到对应的预置字段中；
4. [如何准确识别用户](integration-user-identify.md) ，以便提高用户行为分析的准确性；
5. [分平台上报和跨平台上报](integration-cross-platform.md) 的差异，以便确定是否将多端数据上报到同一个项目中；
6. [如何设计埋点方案](integration-tracking-plan.md)，以便让埋点更满足业务需要

![](../../.gitbook/assets/201901151711159657.jpg)
