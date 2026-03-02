# Mintlify 入门套件

使用此入门套件来部署您的文档并开始自定义。

点击此仓库顶部的绿色 **Use this template** 按钮来复制 Mintlify 入门套件。该套件包含以下示例：

- 指南页面
- 导航
- 自定义选项
- API 参考页面
- 常用组件的使用

**[遵循完整的快速入门指南](https://starter.mintlify.com/quickstart)**

## AI 辅助写作

设置您的 AI 编程工具以配合 Mintlify 使用：

```bash
npx skills add https://mintlify.com/docs
```

此命令将为您的 AI 工具（如 Claude Code, Cursor, Windsurf 等）安装 Mintlify 文档技能。该技能包括组件参考、写作标准和工作流指导。

查看 [AI 工具指南](/ai-tools) 以进行特定工具的设置。

## 开发

安装 [Mintlify CLI](https://www.npmjs.com/package/mint) 以在本地预览文档更改。使用以下命令进行安装：

```bash
npm i -g mint
```

在文档根目录（即 `docs.json` 所在目录）运行以下命令：

```bash
mint dev
```

在 `http://localhost:3000` 查看本地预览。

## 发布更改

从您的 [仪表板](https://dashboard.mintlify.com/settings/organization/github-app) 安装我们的 GitHub 应用，以将更改从仓库同步到部署环境。推送到默认分支后，更改将自动部署到生产环境。

## 需要帮助？

### 故障排除

- 如果开发环境无法运行：运行 `mint update` 以确保您拥有最新版本的 CLI。
- 如果页面显示 404：请确保您在包含有效 `docs.json` 的文件夹中运行。

### 资源
- [Mintlify 文档](https://mintlify.com/docs)
