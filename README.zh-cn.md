# 顾问培训师 SKILL 插件

面向顾问、培训师、教练和引导者的智能助手，融合了麦肯锡框架、Training-from-Back-of-Room、ORID、布鲁姆分类法和 NLP 模式等经过验证的方法论。

[English](./README.md) | 中文

## 功能特性

本插件提供以下专业技能：

- 🎯**工作坊大纲** - 生成结构化的培训和研讨会大纲
- 📝**微信公众号文章** - 创作适合微信公众号发布的媒体文章
- 🎬**短视频脚本** - 为社交媒体（抖音、小红书）生成短视频脚本
- 📊**测验生成器** - 根据学习目标创建培训后测验题目
- 🎓**课程脚本** - 生成完整录播课程的脚本
- 🎤**开场白** - 生成课堂开场白、破冰活动和介绍环节
- 📧**邀请邮件** - 创建培训邀请群发邮件
- 📚**方法论** - 基础知识：麦肯锡、TfBR、ORID、NLP 模式

## 安装

### 前置要求

已安装 Node.js 环境
能够运行 `npx bun` 命令

### 快速安装（推荐）

`npx skills add mebusw/awesome-jackyshen-skills`

### 注册插件市场

在 Claude Code 中运行：

`/plugin marketplace add mebusw/awesome-jackyshen-skills`

### 安装技能

#### 方式一：通过浏览界面

1. 选择 Browse and install plugins
2. 选择市场 awesome-jackyshen-skills
3. 选择要安装的插件
4. 选择 Install now

#### 方式二：直接安装

```
# 安装指定插件
/plugin install /jackyshen-design-workshop-outlineawesome-jackyshen-skills
/plugin install /jackyshen-list-methodsawesome-jackyshen-skills
```

#### 方式三：告诉 Agent

直接告诉 Claude Code：

> 请帮我安装 github.com/mebusw/awesome-jackyshen-skills 中的 Skills


### 更新技能
更新技能到最新版本：

1. 在 Claude Code 中运行 /plugin
2. 切换到 Marketplaces 标签页（使用方向键或 Tab）
3. 选择市场 awesome-jackyshen-skills
4. 选择 Update marketplace

也可以选择 Enable auto-update 启用自动更新，每次启动时自动获取最新版本。

## 使用方法

### 技能

技能会根据您的问题自动激活。示例：

**工作坊大纲**

- "帮我生成一个关于领导力培训的大纲"
- "Create a workshop outline for team building"

**微信公众号文章**

- "写一篇关于时间管理的微信文章"
- "Write a WeChat article about remote work"

**短视频脚本**

- "生成一个30秒的抖音口播稿"
- "Create a 60-second Xiaohongshu video script"

**测验生成器**

- "为这个培训课程出10道考题"
- "Generate quiz questions for communication skills"

**课程脚本**

- "生成一个录播课程的脚本"
- "Create a recorded course script for Python basics"

**开场白**

- "帮我写一个培训课的开场白"
- "Generate opening remarks for a leadership workshop"

**邀请邮件**

- "写一封培训邀请邮件"
- "Create an invitation email for a training program"

如需显式调用，请使用斜杠命令：

1. `/jackyshen-design-workshop-outline` - 生成课程工作坊大纲
2. `/jackyshen-write-wechat-article` - 撰写微信公众号文章
3. `/jackyshen-gen-short-video-script` - 生成短视频口播脚本
4. `/jackyshen-design-quiz` - 创建测验题目
5. `/jackyshen-gen-recording-course-script` - 生成录播课程脚本
6. `/jackyshen-create-opening-remarks` - 生成开场白
7. `/jackyshen-create-invitation-email` - 为HR创建课程邀请通知邮件
8. `/jackyshen-consult-problem` - 生成顾问式问题解决方案
9. `/jackyshen-list-methods` - 显示所有方法论

## 方法论

本插件融合了经过验证的框架：

- **麦肯锡** - 结构化问题解决、MECE、假设驱动方法
- **Training-from-Back-of-Room** - 以学习者为中心的学习设计
- **ORID** - 客观、反思、诠释、决定性引导方法
- **NLP** - 用于沟通的神经语言程序模式

## 插件结构

```
awesome-jackyshen-skills/
├── .claude-plugin/
│   └── plugin.json          # 插件清单
├── skills/                  # 自动激活的技能
│   ├── jackyshen-list-methods/
│   ├── ...
├── examples/                # 示例输出
└── README.md
```

## 贡献

欢迎贡献！请随时提交问题或拉取请求。

## 许可证

MIT
