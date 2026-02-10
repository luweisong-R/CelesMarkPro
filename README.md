# CelesMark Pro - 鸿蒙原生性能测试工具 (专业版)

<div align="center">
    <img src="https://github.com/user-attachments/assets/你的图标链接.png" width="100" height="100" alt="Logo">
    <h3>收款可收集、可玩、可设备评分鸿蒙信息软件</h3>
</div>

## 🚀 软件简介
CelesMark Pro 是一款专为 HarmonyOS NEXT 打造的专业性能基准测试工具。
* **核心引擎**：基于 C++ 编写的 Miludeer v2.0 算法引擎。
* **3D 图形**：内置 Unity 3D 渲染管线，真实反映 GPU 负载能力。
* **完全离线**：无网络权限，纯本地运行，保护隐私。
* **一机一码**：采用离线激活机制，一次激活，永久使用。

## 📥 下载地址
请前往右侧 **[Releases](这里填你的Release页面链接)** 页面下载最新版本。

## 💿 安装教程 (必读)
本软件包含 **UI主程序** 和 **3D引擎** 两个模块，且为 **Unsigned (未签名)** 版本。

**安装步骤：**
1. 下载 Release 中的 `CelesMarkPro_v1.0_Unsigned.zip` 并解压。
2. 使用您的开发者证书对文件夹内的 **两个 .hap 文件** 分别进行重签名。
3. 连接手机，使用 hdc 工具执行以下命令（**注意：必须写在一行同时安装**）：

```bash
hdc install CelesMarkPro_UI.hap CelesMarkPro_3D.hap
