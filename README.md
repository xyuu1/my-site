# 张元英老师个人页面

## 项目简介

这是广东科学技术职业学院商学院商务数据分析与应用专业老师张元英的个人页面，用于展示个人信息和所教授的课程。

## 页面内容

- **个人信息**：展示张老师的照片、姓名、职位和专业背景
- **个人简介**：详细介绍张老师的教学和研究方向
- **课程列表**：展示以下课程信息
  - Python基础
  - 数据分析技术
  - 数据采集与处理
  - 供应链数据分析
  - 数据库应用
- **联系方式**：展示邮箱、办公地点、电话和学院网站

## 技术实现

- **前端**：纯静态HTML + Tailwind CSS v3 + 少量JavaScript
- **部署**：Cloudflare Pages

## 部署指南

### 步骤1：准备工作

1. 确保你已经有一个Cloudflare账号
2. 登录到Cloudflare控制台

### 步骤2：创建Pages项目

1. 在Cloudflare控制台中，选择「Pages」
2. 点击「Create a project」
3. 选择「Connect to Git」或「Direct Upload」

### 步骤3：上传文件

如果选择「Direct Upload」：
1. 点击「Upload assets」
2. 选择本项目中的所有文件（主要是index.html）
3. 点击「Deploy」

如果选择「Connect to Git」：
1. 将本项目推送到GitHub或GitLab仓库
2. 连接该仓库到Cloudflare Pages
3. 配置构建设置（由于是纯静态页面，不需要构建命令）
4. 点击「Deploy」

### 步骤4：访问页面

部署完成后，Cloudflare会生成一个URL，你可以通过该URL访问张老师的个人页面。

## 后续维护

- 如需添加或修改课程信息，直接编辑index.html文件中的课程卡片部分
- 如需更新个人信息，修改相应的HTML内容
- 如需添加新的功能，可在现有的HTML结构基础上进行扩展