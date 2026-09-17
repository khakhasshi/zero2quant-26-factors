# Zero2Quant · 26 个美股因子与回测绩效

**US STOCK NICE FACTORS** 的 KPI 文本副档：整理 26 个因子的 DSL 表达式、数学公式、绩效指标、交易成本与经济学含义，便于阅读、检索和交流。

**[阅读完整文档 →](docs/26-factor-backtest-kpi.md)**

## 加入微信群

欢迎加入 **Zero2Quant量化交易**，交流因子研究与量化交易。

**[微信群邀请链接](https://weixin.qq.com/g/AwYAAHJXXXJFQK2zBg92Zhcs0f-bQBqymvCepsvOApDLZzMUOHHAbzyh9a9zm8AB)** · 建议使用微信扫描下方二维码；若链接无法直接打开，可保存图片后在微信中识别。

<a href="https://weixin.qq.com/g/AwYAAHJXXXJFQK2zBg92Zhcs0f-bQBqymvCepsvOApDLZzMUOHHAbzyh9a9zm8AB">
  <img src="assets/wechat-group.png" alt="Zero2Quant量化交易微信群二维码" width="360">
</a>

二维码图片标注有效期至 **9 月 24 日**。若二维码或邀请链接过期，请发送邮件至 **[contact@jiangjingzhe.com](mailto:contact@jiangjingzhe.com)** 联系我获取最新入群方式，也可在本仓库提交 Issue 请求更新。

## 文档内容

| 内容 | 说明 |
| --- | --- |
| 符号约定 | DSL 算子与数学符号对照 |
| 核心绩效 | 26 个因子的净值、年化、Sharpe、Sortino、Calmar、回撤等 |
| 交易与成本 | 订单、成交、完整交易、佣金税费、滑点与总成本 |
| 机器可读数据 | 原文内嵌 CSV 数据块 |
| 逐因子说明 | DSL 原式、数学式、KPI 与经济学假说 |
| 因子家族 | 动量、反转、低波动、流动性、量价等分类 |

原文记载的回测区间为 **2021-01-04 至 2026-08**，共 **1415 个交易日**，初始资金 **US$1,000,000**，账本模式为 `step_event_v2`。

本次发布保留原始文档内容；仓库收录的是文本资料，不包含净值曲线图、行情数据或回测引擎。本次发布未重新运行回测，原文中的绩效及解释均沿用原始记录。

## 文件

- [完整文档](docs/26-factor-backtest-kpi.md)
- [微信群二维码原图](assets/wechat-group.png)
- [MIT 许可证](LICENSE)

## 许可与引用

本仓库的文档及公式说明采用 **MIT License**，欢迎分享、引用和改进，使用时请保留版权与许可声明。

微信群二维码图片仅用于展示入群入口，不纳入上述许可；图片中的第三方标识和头像权利归各自权利人所有。
