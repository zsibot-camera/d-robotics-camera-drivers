# D-Robotics 相机驱动、SDK 与工具

智身科技（GENISOM AI）视觉传感器团队面向 D-Robotics RDK S600 / S100P 平台的
相机驱动、SDK 与上位机工具发布仓库。

## 支持内容

- **相机驱动**：RDK S600 / S100P 的 MIPI CSI 相机模组驱动
- **统一 SDK**：[ZSCamera_sdk](https://github.com/zsibot-camera/ZSCamera_sdk) —
  C++17 相机与双目深度 SDK，覆盖 RV1126B / Orin NX / AGX Thor
- **上位机工具**：[ZSViewer](https://github.com/zsibot-camera/ZSViewer-delivery) —
  RGB-D 查看、点云、抓图、录像，支持 Linux / Windows（独立交付仓库）

> 驱动与交付包整理中。需要 RV1126B / RDK 现成支持时，请先通过 Issue 或商务渠道联系。

## 交付包

- 统一 SDK（C++ 头文件 + 预编译库 + 模型 + 文档）：
  [ZSCamera_sdk Releases](https://github.com/zsibot-camera/ZSCamera_sdk/releases)
- ZSViewer（Linux / Windows 安装包）：
  [ZSViewer-delivery Releases](https://github.com/zsibot-camera/ZSViewer-delivery/releases/tag/v2.1.0)
- 客户侧 AI 助手：可直接阅读上述 Release 内的 `AI-INSTALL.md`，按平台选择资产、
  校验并一键安装。

## 相关仓库

- [nvidia-jetson-camera-drivers](https://github.com/zsibot-camera/nvidia-jetson-camera-drivers) — NVIDIA Jetson 平台
- [ZSCamera_sdk](https://github.com/zsibot-camera/ZSCamera_sdk) — 统一相机与双目深度 SDK
- [.github](https://github.com/zsibot-camera/.github) — 组织展示页
