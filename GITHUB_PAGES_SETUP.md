# GitHub Pages 部署指南

按照以下步骤将您的个人网站部署到GitHub Pages：

## 步骤1：创建GitHub账号（如果还没有）

1. 访问 [GitHub](https://github.com)
2. 点击注册，填写相关信息创建账号

## 步骤2：创建新的仓库

1. 登录GitHub账号后，点击右上角的"+"图标，选择"New repository"
2. 仓库名称格式必须是：`用户名.github.io`（用您的GitHub用户名替换"用户名"）
3. 选择"Public"（公开）
4. 不需要勾选"Initialize this repository with a README"
5. 点击"Create repository"按钮创建仓库

## 步骤3：上传网站文件到GitHub仓库

### 方法1：使用Git命令行（推荐）

在终端或命令提示符中执行以下命令：

```bash
# 进入您的网站目录
cd 您的网站目录路径

# 初始化Git仓库
git init

# 添加所有文件到暂存区
git add .

# 提交更改
git commit -m "Initial commit"

# 添加远程仓库
git remote add origin https://github.com/用户名/用户名.github.io.git

# 推送到GitHub
git push -u origin main
```

### 方法2：使用GitHub Desktop

1. 下载并安装 [GitHub Desktop](https://desktop.github.com/)
2. 登录您的GitHub账号
3. 添加本地仓库（选择您的网站文件夹）
4. 填写提交信息并提交
5. 点击"Publish repository"
6. 选择您创建的`用户名.github.io`仓库
7. 点击"Publish"按钮

## 步骤4：配置GitHub Pages

1. 在GitHub上打开您的仓库页面
2. 点击仓库上方的"Settings"选项卡
3. 在左侧菜单栏中找到并点击"Pages"
4. 在"Source"部分，选择"main"分支
5. 点击"Save"按钮

## 步骤5：等待部署

GitHub Pages可能需要几分钟时间来部署您的网站。部署完成后，您将看到一条消息，显示您的网站已发布在`https://用户名.github.io`。

## 步骤6：访问您的网站

在浏览器中输入`https://用户名.github.io`即可访问您的个人网站。

## 更新网站

当您对网站进行更改后：

1. 使用Git命令行（如果您使用方法1）：
   ```bash
   git add .
   git commit -m "更新描述"
   git push
   ```

2. 使用GitHub Desktop（如果您使用方法2）：
   - 提交您的更改
   - 点击"Push origin"按钮

更改推送到GitHub后，GitHub Pages会自动更新您的网站。

## 自定义域名（可选）

如果您有自己的域名，可以在GitHub Pages设置页面的"Custom domain"部分添加您的域名，并按照说明设置DNS记录。

## 注意事项

- 确保您的主页文件名为`index.html`
- GitHub Pages支持静态文件（HTML、CSS、JavaScript等），不支持服务器端语言（如PHP）
- 如果部署后网站样式或功能不正常，请检查文件路径是否正确 