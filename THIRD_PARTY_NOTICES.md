# 第三方内容 / Third-party materials

AERO 的原创部分由 Aeolus 署名。项目的作者授权许可不替代或限制第三方各自的许可，也不将第三方内容声明为 Aeolus 原创。

## 软件依赖 / Software dependencies

本地包元数据已核对：React / React DOM、Electron 和 Vite 为 MIT，lucide-react 为 ISC，TypeScript 为 Apache-2.0。完整依赖版本见 `package-lock.json`；分发时须遵守实际随包分发的各依赖许可证并保留所需声明。本文件不是完整传递依赖许可证清单。

界面内打包的 React、React DOM、scheduler 与 lucide-react 完整许可保存在 [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md)。Windows 便携包另保留 `LICENSE.electron.txt` 与 `LICENSES.chromium.html`，不会用 AERO 的许可覆盖 Electron 或 Chromium 的权利声明。

离线语音使用 Vosk、sounddevice、Python、uv 和外部下载的模型；它们不受 AERO 作者许可约束。模型和独立运行环境不纳入源码仓库，安装与分发仍应遵守来源项目各自的条款。

## 产品网站动效 / Website motion

产品网站构建使用 GSAP 3.15.0（[GSAP Standard License](https://gsap.com/standard-license/)）与 Lenis 1.3.27（MIT）。它们作为网站开发依赖保存，构建后随静态网站分发；不通过 AERO 原创许可重新授权。具体条款以随依赖提供的文件和来源项目为准。

## 从 Codex 提取的图标 / Extracted Codex icons

`public/codex-icons/*.svg` 来源于 Codex Desktop 安装包，提取路径和映射见 `scripts/mirror-codex-micro-icons.cjs`；`manifest.json` 是资源路径索引。这些图标及 OpenAI / Codex 标识不是 Aeolus 原创，不受 AERO 的原创内容许可重新授权。

## 品牌和其他工作区内容 / Brands and workspace references

OpenAI、Codex 及第三方标识归各自权利人。本项目是独立项目，不声明获得 OpenAI 官方认可或与其关联。

工作区中的 Codex 接口提取、第三方参考项目与网页参考素材，不因与 AERO 共处同一目录而受到 AERO 许可覆盖。计划发布的仓库应以本应用仓库为边界，不将整个资料工作区直接上传。
