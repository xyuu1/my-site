<<<<<<< HEAD
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
=======
# 肖老师个人主页

这是广东科学技术职业学院商学院商务数据分析与应用专业肖老师的个人主页。

## 技术栈

- HTML5
- Tailwind CSS
- Font Awesome
- JavaScript

## 功能特点

- 科技风格设计，深色背景搭配霓虹色彩
- 响应式设计，适配不同设备屏幕
- 动态效果和动画，增强用户体验
- 平滑的滚动效果
- 回到顶部按钮
- 导航栏滚动效果
- AI编程相关内容模块
- 教学成果展示
- 联系方式表单

## 项目结构

```
├── index.html          # 主页面
└── README.md           # 项目说明
```

## 部署步骤

### 1. 推送到GitHub

1. 初始化Git仓库
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. 创建GitHub仓库并推送
   ```bash
   git remote add origin https://github.com/xyuu1/my-site.git
   git push -u origin main
   ```

### 2. 部署到Cloudflare Pages

1. 登录Cloudflare账户
2. 导航到Pages部分
3. 点击"Create a project"
4. 选择连接到GitHub仓库
5. 选择你的仓库
6. 配置构建设置：
   - 构建命令：留空（纯静态网站）
   - 构建输出目录：`/`
7. 点击"Save and Deploy"
8. 部署完成后，Cloudflare会提供一个域名

## 自定义修改

1. 修改个人信息：编辑`index.html`文件中的个人信息部分
2. 修改AI编程内容：编辑对应的section部分
3. 修改教学成果：更新教学理念和学生成果部分
4. 修改联系方式：更新联系信息部分
5. 修改样式：可以在`tailwind.config`中调整颜色和字体

## 预览

你可以通过以下方式预览网站：
- 直接在浏览器中打开`index.html`文件
- 通过GitHub Pages预览
- 通过Cloudflare Pages预览

## 许可证

MIT License
>>>>>>> 34f9679fdc1297763c72fd94d80f48ae97ebae48
