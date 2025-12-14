# 自用 VS Code IntelliJ 暗色主题微调

> ⚠️ 本仓库内容为**个人自用配置**，仅供学习与参考。不保证兼容性或长期维护。

## 简介

本项目包含我从 VS Code 的 `settings.json` 中提取出的部分配置，主要用于**自定义代码片段的语法高亮颜色**。这些设置基于 [IntelliJ IDEA New UI Theme](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-theme-intellij-new-ui) 插件中的 **Dark Theme** 风格进行微调，以更贴合我个人的视觉偏好和编码习惯。

## 使用说明

1. 安装 [Intelli IDEA New UI Theme](https://marketplace.visualstudio.com/items?itemName=ms-vs# 自用 VS Code 代码高亮配色配置

> ⚠️ 本仓库内容为**个人自用配置**，仅供学习与参考。不保证兼容性或长期维护。

## 简介

本项目包含我从 VS Code 的 `settings.json` 中提取出的部分配置，主要用于**自定义代码片段的语法高亮颜色**。这些设置基于 [IntelliJ IDEA New UI Theme](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-theme-intellij-new-ui) 插件中的 **Dark Theme** 风格进行微调，以更贴合我个人的视觉偏好和编码习惯。

## 使用说明

1. 安装 [Intelli IDEA New UI Theme](https://marketplace.visualstudio.com/items?itemName=compassak.intellij-idea-new-ui) 插件。(这是我见过的模仿idea主题最像的插件)
2. 将 `Semantic Highlighting` 设置为 `false`
3. 将本仓库中的相关配置处理后复制到你的 VS Code `settings.json` 文件中（可通过 `Ctrl/Cmd + Shift + P` → 输入 “Preferences: Open Settings (JSON)” 打开）。
4. 根据需要自行调整颜色值或作用域（scope）。

## 注意事项

- 此配置**未经过全面测试**，可能在某些语言或插件下表现异常。
- **不建议直接用于生产环境**，请务必先在本地备份原配置。
- 此配置主要针对 **Python** 的语法高亮，因此该配置不能完全贴合JetBrains旗下所有IDE
- 此配置主要针对**关闭语义高亮**下的情况，开启时有些配置会被覆盖


## 许可

无特定开源协议。你可以自由参考、修改或使用其中的内容，但作者不承担任何责任。

---

✨ 欢迎交流，但请理解此为私人配置，**不接受功能请求或 Issue 报告**。code.vscode-theme-intellij-new-ui) 插件。
2. 将本仓库中的相关配置复制到你的 VS Code `settings.json` 文件中（可通过 `Ctrl/Cmd + Shift + P` → 输入 “Preferences: Open Settings (JSON)” 打开）。
3. 根据需要自行调整颜色值或作用域（scope）。

## 注意事项

- 此配置**未经过全面测试**，可能在某些语言或插件下表现异常。
- 配色方案高度依赖 IntelliJ IDEA New UI Theme 的底层 tokenization，若主题更新，可能需要同步调整。
- **不建议直接用于生产环境**，请务必先在本地备份原配置。

## 许可

无特定开源协议。你可以自由参考、修改或使用其中的内容，但作者不承担任何责任。

---

✨ 欢迎交流，但请理解此为私人配置，**不接受功能请求或 Issue 报告**。