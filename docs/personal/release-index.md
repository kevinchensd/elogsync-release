# 一录清个人版版本索引 / ELogSync Personal release index

## English

| Version | Status | Platforms | Database schema upgrade | Release |
| --- | --- | --- | --- | --- |
| v0.1.20 | Stable | Windows x64 NSIS | Yes | `personal-v0.1.20` |
| v0.1.19 | Stable | Windows x64 NSIS | No | `personal-v0.1.19` |
| v0.1.18 | Stable | Windows x64 NSIS | Yes | `personal-v0.1.18` |
| v0.1.15 | Stable | Windows x64 NSIS | No | `personal-v0.1.15` |
| v0.1.10 | Stable | Windows x64 NSIS | Yes | `personal-v0.1.10` |

### Upgrade guidance

If a release has no database schema upgrade, it can be installed directly across application-version gaps. If a release has a database schema upgrade, install each earlier release marked **Yes** in order before installing the target release. Back up local data before every schema upgrade.

## 简体中文

| 版本 | 状态 | 平台 | 是否有数据库结构升级 | 发布 Tag |
| --- | --- | --- | --- | --- |
| v0.1.20 | 正式版 | Windows x64 NSIS | 有 | `personal-v0.1.20` |
| v0.1.19 | 正式版 | Windows x64 NSIS | 无 | `personal-v0.1.19` |
| v0.1.18 | 正式版 | Windows x64 NSIS | 有 | `personal-v0.1.18` |
| v0.1.15 | 正式版 | Windows x64 NSIS | 无 | `personal-v0.1.15` |
| v0.1.10 | 正式版 | Windows x64 NSIS | 有 | `personal-v0.1.10` |

### 升级说明

如果发布版本没有数据库结构升级，可以跨应用版本直接安装。若发布版本有数据库结构升级，请先按顺序安装历史版本中标注“有”的结构升级安装包，再安装目标版本。每次数据库结构升级前请先备份本机数据。
