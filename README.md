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
   git remote add origin https://github.com/yourusername/your-repo-name.git
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