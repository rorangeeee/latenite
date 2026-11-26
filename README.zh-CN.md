# Latenite 主题
[English](README.md) | [简体中文](README.zh-CN.md)

## 概述

Latenite 是一款深色 VS Code 主题，采用**黑紫**配色方案，**低饱和度**，并配有**暗色调的语法高亮**，主要为夜间编程场景设计。代码纯天然（AI），零人工添加成分。

## 变体

- **latenite** —— 黑紫配色，原始深色主题。
- **latenite dawn** —— 对应的浅色版本：同样的暗调语法色，铺在淡紫底色（`#C6ACE0`）上，配深紫墨色与 `#40009E` 强调色。

## 创建方式

本主题使用 [Yeoman](https://yeoman.io/) 和 [VS Code 扩展生成器](https://www.npmjs.com/package/generator-code) 生成，该工具提供了构建自定义主题的脚手架结构。

## 设计理念

- **深色低饱和调色板**：语法高亮色被刻意降低亮度，以匹配主文本色的亮度水平，减少长时间使用时的视觉疲劳。
- **黑紫色强调**：主强调色为 `#7B68EE`（MediumSlateBlue），仅用于激活元素和聚焦状态，使用克制。
- **个人偏好驱动**：本主题主要为满足我个人的工作流程和偏好而定制，并非面向所有用户的通用主题。

## 支持的语言环境

本主题主要经过以下语言的测试和优化：

- **C** / **C++**
- **Python**
- **Markdown**
- **纯文本 (TXT)**

虽然其他语言环境下可能也能正常使用，但**不保证**在其他语言（如 Java、JavaScript、Rust 等）中的可读性和视觉一致性。

## 安装

### 方式一：GitHub Release（手动安装）

1. 从 [Releases](https://github.com/rorangeeee/latenite/releases) 页面下载最新的 `.vsix` 文件。
2. 打开 VS Code。
3. 按 `Ctrl+Shift+P`（macOS 为 `Cmd+Shift+P`）打开命令面板。
4. 执行 `Extensions: Install from VSIX...`。
5. 选择下载的 `.vsix` 文件。

### 方式二：VS Code 应用商店

*(若已发布)*

1. 在 VS Code 中打开扩展视图（`Ctrl+Shift+X`）。
2. 搜索 `Latenite`。
3. 点击 **安装**。

## 参与贡献

本主题是一个持续迭代的个人项目。我欢迎以下形式的贡献：

- 通过 [GitHub Issues](https://github.com/rorangeeee/latenite/issues) 提交 **缺陷报告** 或 **可读性问题**。
- 提交 **Pull Request** 以改进主题或增加对其他语言的支持。
- **Fork** 本项目进行个人定制 —— 欢迎自由修改，打造属于你自己的版本。
