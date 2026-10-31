# CLAUDE.md - QQ 名片点赞 (github_FleetingEternity-qyt_qq-like)

## 1. 模块定位与系统职责
- **插件标识符**：`github_FleetingEternity-qyt_qq-like`
- **当前生效版本**：`v1.0.1`
- **托管仓库**：[`Wenaixi/qq-like`](https://github.com/Wenaixi/qq-like)
- **核心定位**：支持通过指令或自然语言请求麦麦为自己的 QQ 名片或说说点赞。

## 2. 关键工程规范与配置说明
- **配置路径**：`config.toml`（所有业务调优与鉴权参数收敛于此）；
- **数据持久化**：优先遵循 MaiBot SDK 标准持久化规范，不直接向源码目录写入易失数据；
- **编码与日志规范**：严格遵循 PEP 8 风格，文档与代码注释杜绝 emoji，避免虚假套话。

## 3. 本地深度定制与稳定性修复
解除了默认 admin_only 导致的无法使用，开放好友点赞功能（单日 30 次与 30 秒冷却双重防风控保护），管理员设为主人的 QQ。

---

## 上游项目与开源溯源
- **原作者 / 组织**：`FleetingEternity-qyt`
- **官方上游仓库**：[https://github.com/FleetingEternity-qyt/qq-like](https://github.com/FleetingEternity-qyt/qq-like)
- **开源许可证**：`GPL-3.0`
- **分支演进模式**：本仓库作为主人的深度定制与生产维护分支（`Wenaixi/qq-like`）。在保持与官方上游架构演进对齐的同时，锁死并持续维护针对本服务器生产环境的稳定性补丁与核心特性。
