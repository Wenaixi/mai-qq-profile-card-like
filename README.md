# QQ 名片点赞

[![Release](https://img.shields.io/github/v/release/Wenaixi/mai-qq-profile-card-like?style=flat-square&color=blue&label=release)](https://github.com/Wenaixi/mai-qq-profile-card-like/releases)
[![CI](https://img.shields.io/github/actions/workflow/status/Wenaixi/mai-qq-profile-card-like/ci.yml?branch=main&style=flat-square&label=CI)](https://github.com/Wenaixi/mai-qq-profile-card-like/actions)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.12%20%7C%203.13-blue?style=flat-square)](https://www.python.org/)
[![MaiBot](https://img.shields.io/badge/MaiBot-1.2%2B-orange?style=flat-square)](https://docs.mai-mai.org)

> 本插件由 [Wenaixi](https://github.com/Wenaixi) 维护，是专为生产环境深度调优的高可用分支。

## 简介与定位

支持通过命令或自然语言请求麦麦为自己的 QQ 名片点赞。

- **插件目录**：`wenaixi_mai_qq_profile_card_like`
- **开源许可证**：`GPL-3.0`

---

## 核心特性与本地深度调优

- 放开 admin_only 限制，允许好友与群友点赞（受单日 30 次与 30s 冷却保护）
- 将管理员设为主人的 QQ (121645025)

---

## 指令与工具速查

### 常用指令 (Command)
- `/qq_like 或 /赞 - 请求麦麦给自己的名片点赞`

### 大模型工具 (Tool)
- `@Tool("like_qq_profile") - 麦麦大模型自主点赞工具`

---

## 快速配置

配置文件统一定位于插件根目录下的 `config.toml`。修改后重启或通过 WebUI 热重载即可生效。

---

## 上游项目与开源溯源

- **原作者 / 组织**：`FleetingEternity-qyt`
- **官方原版开源仓库**：[https://github.com/FleetingEternity-qyt/qq-like](https://github.com/FleetingEternity-qyt/qq-like)
- **开源协议**：`GPL-3.0`
- **声明**：本项目遵循开源协议，特此致敬原作者的杰出贡献。本分支针对生产环境的高并发网络、个性化社交和抗风控需求进行了深度稳定性修复与定制化演进。