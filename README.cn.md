# ripgrep-all

[English version](./README.md)

rga: ripgrep, but also search in PDFs, E-Books, Office documents, zip, tar.gz, etc.

![ripgrep-all](https://repo.x-cmd.io/ripgrep-all.svg?lang=zh)

## 安装

```sh
x install ripgrep-all
```

## 代码规模

合计: **3,490** 行代码（覆盖前 5 种语言、共 **34** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Rust | 3,297 | 259 | 322 | 24 |
| Nix | 108 | 0 | 1 | 1 |
| Toml | 71 | 1 | 5 | 2 |
| Sh | 14 | 3 | 5 | 3 |
| Markdown | 0 | 811 | 253 | 4 |

## OpenSSF Scorecard 评分

总评分: **2.9 / 10**

评分最低的几项:

- **Maintained** (0/10) — 0 commit(s) and 0 issue activity found in the last 90 days -- score normalized to 0
- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## 源代码

- **上游仓库**: <https://github.com/phiresky/ripgrep-all>
- **许可证**: NOASSERTION

## 发布

- **最新版本**: `v0.10.10` (2025-11-09)
- **最近提交**: 2026-03-25
- **Release 含资产**: 5 个

## 流行度

- **Star**: 9,840 · **Fork**: 216 · **开放 issue**: 227 · **贡献者**: 34

## 累计统计

- **发布数**: 12 · **已合并 PR**: 57 · **开放 PR**: 9 · **已关闭 issue**: 163 · **开放 issue**: 64 · **提交数**: 462

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-12 | 0 | 0 | 0 | 0 | 1 | 0 |
| 90d | 2026-06-12 | 0 | 0 | 0 | 0 | 1 | 0 |
| last180d | 2026-03-14 | 0 | 1 | 0 | 0 | 7 | 2 |
| 360d | 2025-09-15 | 1 | 4 | 5 | 5 | 11 | 8 |
| last720d | 2024-09-20 | 3 | 14 | 7 | 14 | 34 | 45 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [ripgrep_all-v0.10.10-aarch64-apple-darwin.tar.gz](https://github.com/phiresky/ripgrep-all/releases/download/v0.10.10/ripgrep_all-v0.10.10-aarch64-apple-darwin.tar.gz) | 6.7 MiB | `native/darwin/arm64` |
| [ripgrep_all-v0.10.10-aarch64-unknown-linux-gnu.tar.gz](https://github.com/phiresky/ripgrep-all/releases/download/v0.10.10/ripgrep_all-v0.10.10-aarch64-unknown-linux-gnu.tar.gz) | 6.9 MiB | `native/linux/arm64/glibc` |
| [ripgrep_all-v0.10.10-arm-unknown-linux-gnueabihf.tar.gz](https://github.com/phiresky/ripgrep-all/releases/download/v0.10.10/ripgrep_all-v0.10.10-arm-unknown-linux-gnueabihf.tar.gz) | 6.8 MiB | `native/linux/arm/glibc` |
| [ripgrep_all-v0.10.10-x86_64-apple-darwin.tar.gz](https://github.com/phiresky/ripgrep-all/releases/download/v0.10.10/ripgrep_all-v0.10.10-x86_64-apple-darwin.tar.gz) | 7.3 MiB | `native/darwin/x64` |
| [ripgrep_all-v0.10.10-x86_64-unknown-linux-musl.tar.gz](https://github.com/phiresky/ripgrep-all/releases/download/v0.10.10/ripgrep_all-v0.10.10-x86_64-unknown-linux-musl.tar.gz) | 8.0 MiB | `native/linux/x64/musl` |

## 发行版状态

在 [repology.org](https://repology.org/project/ripgrep-all) 上共有 **46** 个发行版报告此项目。**37** 个 ✅ 已是最新上游版本，**4** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `0.10.10` | ✅ latest |
| Debian 14 | `0.10.10` | ✅ latest |
| Ubuntu 26.04 LTS | `0.10.10` | ✅ latest |
| Arch | `0.10.10` | ✅ latest |
| Homebrew | `0.10.10` | ✅ latest |
| Nix unstable | `0.10.10` | ✅ latest |
| Void | `0.10.10` | ✅ latest |

## 改进这些数据

ripgrep-all 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `ripgrep-all` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/ripgrep-all.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T21:36:02Z._
