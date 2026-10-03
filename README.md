# 碎碎记 CutShelter — 下载与发布

> 本仓库**仅用于分发编译产物**，不包含源代码。

🧭 官网：[https://cutshelter.pages.dev](https://cutshelter.pages.dev)

## 下载

前往 [**Releases**](https://github.com/wf-Peg/CutShelter-Releases/releases/latest) 获取最新版本：

| 产物 | 说明 |
| :--- | :--- |
| `CutShelter-Setup-x.y.z.exe` | Windows 安装版（NSIS，可选安装目录） |
| `CutShelter-portable-x.y.z-win-x64.zip` | Windows 免安装便携版 |
| `clip-update-x.y.z.zip` + `.sha256` | 应用内增量更新包与 SHA-256 校验文件 |
| `CutShelter-webclipper-x.y.z.zip` | 浏览器插件（Web Clipper） |

> 增量更新包只替换应用的 `resources/`，**不替换 Electron 运行时**，因此仅适用于与之同源的主版本；跨版本请下载完整安装包。

## 更新说明

每个 Release 的说明中会记录该版本的主要变更。

## 授权

本仓库仅分发编译产物，源代码不公开。软件版权归作者所有（All Rights Reserved）。
