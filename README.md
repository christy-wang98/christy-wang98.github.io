# Personal Profile Website

This is a personal profile static website built with HTML, CSS, and JavaScript, designed to be deployed on GitHub Pages.

## Features

- Responsive design for all devices
- Modern minimalist UI design
- Personal information display
- Skills and expertise showcase
- Projects/portfolio gallery
- Education and work experience
- Contact information and social media links

## File Structure

```
.
├── index.html          # Main page
├── css/                # Style directory
│   └── style.css       # Main stylesheet
├── js/                 # JavaScript directory
│   └── main.js         # Main script file
└── assets/             # Assets directory
    ├── images/         # Image resources
    └── icons/          # Icon resources
```

## Usage

1. Customize your personal information by modifying the HTML file
2. Adjust styles in CSS as needed
3. Deploy using GitHub Pages

## Deploying to GitHub Pages

1. Create a new repository on GitHub named `{your-username}.github.io`
2. Push the project files to this repository
3. Enable GitHub Pages in the repository settings, selecting the main branch as the source
4. After a few minutes, your website will be live at `https://{your-username}.github.io`

## Customization Guide

- **Personal Information**: Modify the relevant sections in index.html
- **Style Adjustments**: Edit the css/style.css file
- **Adding Projects**: Add new project cards in the projects section
- **Changing Images**: Place your photos in the assets/images directory and update paths in HTML

## Last Updated

April 28, 2023

## License

MIT 

## 项目介绍
这是一个个人专业网站，用于展示Chunyan (Christy) Wang的专业背景、技能、项目经验和联系方式。网站使用HTML、CSS和JavaScript构建，并通过GitHub Pages部署。

## 功能特点
- 个人专业信息展示
- 技能水平可视化
- 项目展示
- 工作经验和教育背景
- 联系方式

## 部署说明
该网站通过GitHub Pages部署，可以通过 https://christy-wang98.github.io 访问。

## 更新内容
- 将网站语言从中文更新为英文
- 更新个人专业信息
- 添加技能分类展示
- 更新项目和工作经验

## 如何添加个人照片
1. 准备一张专业照片
2. 将照片命名为`profile-photo.jpg`
3. 将照片文件保存到项目的`images`目录中：`/Users/chunyanwang/项目开发/个人网页/images/`
4. 保存后，您可以在本地通过浏览器打开`index.html`文件预览效果
5. 满意后，使用Git命令将更改推送到GitHub:
   ```
   git add images/profile-photo.jpg
   git commit -m "Add professional profile photo"
   git push origin main
   ```
6. 等待几分钟后，您的个人网站将更新显示新照片

## 本地预览
您可以通过直接在浏览器中打开`index.html`文件来预览网站。

## 技术栈
- HTML5
- CSS3 (Bootstrap框架)
- JavaScript
- GitHub Pages (用于部署) 