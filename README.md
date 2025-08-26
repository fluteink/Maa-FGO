<!-- markdownlint-disable MD033 MD041 -->
<p align="center">
  <img alt="LOGO" src="https://cdn.jsdelivr.net/gh/MaaAssistantArknights/design@main/logo/maa-logo_512x512.png" width="256" height="256" />
</p>

<div align="center">

# Maa-FGO

</div>

<p align="center">
  基于 <a href="https://github.com/MaaXYZ/MaaFramework">MaaFramework</a> 的 FGO 自动化助手
</p>

本项目是基于 [MaaFramework](https://github.com/MaaXYZ/MaaFramework) 开发的 FGO(Fate/Grand Order) 自动化助手，旨在帮助玩家自动完成日常任务，提高游戏体验。

> **MaaFramework** 是基于图像识别技术、运用 [MAA](https://github.com/MaaAssistantArknights/MaaAssistantArknights) 开发经验去芜存菁、完全重写的新一代自动化黑盒测试框架。
> 低代码的同时仍拥有高扩展性，我们将利用这个框架为 FGO 玩家提供便捷的自动化功能。

## 功能特性 (TODO)

- [ ] 自动登录游戏
- [ ] 自动领取奖励（登录奖励、活动奖励等）
- [ ] 自动完成日常任务
- [ ] 自动刷材料/经验本
- [ ] 自动完成活动任务
- [ ] 更多功能正在开发中...

## 快速开始

### 环境准备

1. 克隆本项目及子项目：

    ```bash
    git clone https://github.com/YourUsername/Maa-FGO.git
    cd Maa-FGO
    ```

2. 下载 MaaFramework 的 [Release 包](https://github.com/MaaXYZ/MaaFramework/releases)，解压到 `deps` 文件夹中。

3. 下载通用资源子模块（MaaCommonAssets）：

    ```bash
    git submodule update --init --recursive
    ```

4. 配置资源文件：

    ```bash
    python ./configure.py
    ```

### 使用方法

1. 确保 FGO 游戏已安装并可以正常运行
2. 启动本项目中的 MaaFGO 程序
3. 根据界面提示进行相关设置
4. 选择需要执行的自动化功能
5. 运行程序并保持游戏窗口可见

## 开发指南

如果您希望参与本项目的开发，可以按照以下步骤进行：

1. Fork 本项目

2. 克隆您的 Fork 仓库：

    ```bash
    git clone https://github.com/YourUsername/Maa-FGO.git
    cd Maa-FGO
    ```

3. 安装依赖并配置环境（参考快速开始部分）

4. 进行开发工作：
   - 在 `assets` 目录中添加或修改资源文件
   - 在 `agent` 目录中编写自定义动作和识别逻辑

5. 测试您的修改

6. 提交 Pull Request

## 常见问题

### 1. OCR 文字识别没有结果，报错 "Failed to load det or rec", "ocrer_ is null"

请确保已正确下载 MaaCommonAssets 子模块，目录结构应为 `assets/MaaCommonAssets/OCR`。

### 2. 程序无法识别游戏界面

请确保：
- 游戏窗口完全显示在屏幕上
- 没有其他窗口遮挡游戏画面
- 游戏分辨率设置为推荐分辨率

### 3. 其他问题

如果遇到其他问题，请查看 [MaaFramework FAQ](https://github.com/MaaXYZ/MaaFramework/blob/main/docs/zh_cn/3.1-FAQ.md) 或在本项目提交 issue。

## 鸣谢

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！

感谢所有为本项目作出贡献的开发者：

[![Contributors](https://contrib.rocks/image?repo=MaaXYZ/MaaFramework&max=1000)](https://github.com/MaaXYZ/MaaFramework/graphs/contributors)