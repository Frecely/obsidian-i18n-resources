# obsidian-i18n-resources
# Obsidian 翻译文件共享仓库
> 基于 Obsidian i18 插件生成的翻译文件仓库，用于同步、分享和协作维护多语言笔记。

## 📖 简介

本仓库用于存放通过 **Obsidian i18 插件** 翻译后的 Markdown 文件。  
你可以直接克隆本仓库，并用 Obsidian 打开，即可查看或继续编辑翻译内容。

适合以下场景：

- 在不同设备之间同步翻译结果
- 分享自己翻译好的 Obsidian 笔记
- 与其他人协作完善多语言版本
- 作为翻译文件的备份仓库

## ✨ 特性

- 由 Obsidian i18 插件生成，保持 Markdown 格式
- 可直接作为 Obsidian vault 使用
- 支持按语言分目录管理
- 已忽略 Obsidian 工作区等易冲突文件
- 可通过 Git 插件自动同步

## 🚀 快速开始

### 1. 克隆仓库

```bash
git clone https://github.com/你的用户名/你的仓库名.git
```

### 2. 用 Obsidian 打开

1. 打开 Obsidian
2. 点击“管理仓库”
3. 选择“打开本地仓库”
4. 选择刚刚克隆下来的文件夹

### 3. 安装并配置 i18 插件

1. 在 Obsidian 社区插件中搜索并安装 **i18** 插件
2. 启用插件
3. 在插件设置中配置语言模型 API
4. 确保 API 账户余额充足，避免出现 `Insufficient Balance` 错误

### 4. 同步翻译文件

你可以使用以下任一方式提交和推送更改：

- Obsidian Git 插件
- GitHub Desktop
- Git 命令行

推荐使用 Obsidian Git 插件，可在 Obsidian 内部完成自动同步。

## 🔄 同步说明

### 使用 Obsidian Git 插件

1. 安装并启用 Obsidian Git 插件
2. 执行 `Git: Initialize a new repo`
3. 执行 `Git: Edit remotes`，关联本仓库地址
4. 执行 `Git: Set upstream branch`，选择 `origin/main`
5. 提交并推送更改

可开启以下自动同步选项：

- Auto commit after stopping file edits
- Auto pull interval
- Pull on startup

### 使用命令行

```bash
git add .
git commit -m "更新翻译文件"
git push
```

## ⚠️ 注意事项

- 请勿提交 `.obsidian/workspace.json`、`.obsidian/workspace-mobile.json` 等易冲突文件
- 多设备同步前，建议先拉取最新更改
- 如果使用 API 翻译，请注意账户余额和 Token 消耗
- 大文件请谨慎提交，GitHub 对单文件大小有限制
