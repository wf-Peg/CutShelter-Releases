# 碎碎记 CutShelter — 下载与发布

> 本仓库**仅用于分发编译产物**，不包含源代码。

🧭 官网：[https://cutshelter.pages.dev](https://cutshelter.pages.dev)

## 下载

前往 [**Releases**](https://github.com/wf-Peg/CutShelter-Releases/releases/latest) 获取最新版本：

| 产物 | 平台 | 说明 |
| :--- | :--- | :--- |
| `CutShelter-Setup-x.y.z.exe` | Windows | 安装版（NSIS，可选安装目录） |
| `CutShelter-portable-x.y.z-win-x64.zip` | Windows | 免安装便携版（解压即用） |
| `CutShelter-x.y.z-arm64.dmg` | macOS | 安装镜像，Apple 芯片（M 系列） |
| `CutShelter-x.y.z-x64.dmg` | macOS | 安装镜像，Intel 芯片 |
| `CutShelter-x.y.z-arm64.zip` | macOS | 免安装版，Apple 芯片（解压即用） |
| `CutShelter-x.y.z-x64.zip` | macOS | 免安装版，Intel 芯片（解压即用） |
| `clip-update-x.y.z.zip` + `.sha256` | 通用 | 应用内增量更新包与 SHA-256 校验文件 |
| `CutShelter-webclipper-x.y.z.zip` | 通用 | 浏览器插件（Web Clipper） |

> **macOS 该下哪个**：不确定芯片型号时，打开「关于本机」查看——Apple 芯片（M1/M2/M3/M4…）选 `arm64`，Intel 选 `x64`。
>
> ⚠️ **macOS 产物未做代码签名**，首次打开会被 Gatekeeper 拦截：在「应用程序」中**右键 →「打开」**（或到 系统设置 → 隐私与安全性 →「仍要打开」）确认一次即可，之后可正常双击启动。
>
> 增量更新包只替换应用的 `resources/`，**不替换 Electron 运行时**，因此仅适用于与之同源的主版本（Windows 与 macOS 均适用）；跨版本请下载完整安装包。

## 更新说明

每个 Release 的说明中会记录该版本的主要变更。

## 授权

本仓库仅分发编译产物，源代码不公开。软件版权归作者所有（All Rights Reserved）。
