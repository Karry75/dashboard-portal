# 两轮车换电 / 租车 · 运营数据看板作品集

本仓库是**看板作品集导航页**：一个单文件静态页面，集中收录两轮车换电与租车业务的全部数据看板入口，点击即进入对应在线看板。

在线访问：https://karry75.github.io/dashboard-portal/

## 技术速览

- **形态**：单文件静态页面（HTML + CSS），无构建步骤、无后端依赖；托管于 GitHub Pages。
- **原理**：纯前端锚点/链接跳转，页面本身不加载任何业务数据，仅作为各看板子站的统一入口，避免分散链接与失效。
- **用途**：为「深圳嘟嘟换电 / 租车」业务的运营看板作品提供统一导航，便于快速演示与按需进入子系统。

## 收录看板

| 看板 | 地址 |
|------|------|
| 嘟嘟换电统一看板 | https://karry75.github.io/citybike-unified/ |
| 城市换电业务看板（全量） | https://karry75.github.io/citybike-dashboard/ |
| 城市换电业务看板（静态发布版） | https://karry75.github.io/citybike-pub/ |
| 换电运营平台数据快照 | https://karry75.github.io/battery-swap-dashboard/ |
| 用户经营看板（押金划扣 & 沉默低频） | https://karry75.github.io/user-ops-board/ |
| 网点价值与财务收支看板 | https://karry75.github.io/board-value/ |
| 电费管理系统看板 | https://karry75.github.io/elec-fee-dashboard/ |
| 电费管理系统（静态快照） | https://karry75.github.io/electric-fee-system/ |
| 电动自行车换电行业趋势分析看板 | https://karry75.github.io/exchange-trend-dashboard/ |
| 低频用户 · 欠租催收智能回访看板 | https://karry75.github.io/lowfreq-dashboard/ |
| 深圳嘟嘟租赁车辆名单 | https://karry75.github.io/rental-ledger-dashboard/ |
| 设备预警看板（换电柜 / 电池） | https://karry75.github.io/dudu-dashboard/ |

## 脱敏说明

- 全部看板为**已脱敏的静态快照**：移除数据库连接信息与账号口令，手机号/身份证等个人字段做掩码处理，物理表名统一改名。
- 本仓库不含任何业务数据文件与凭据。
