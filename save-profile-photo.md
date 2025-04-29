# 如何添加个人照片到您的网站

## 步骤说明

1. **准备您的专业照片**
   - 选择一张专业的、清晰的个人照片
   - 理想尺寸：建议使用方形或接近方形的照片（例如500x500像素）
   - 文件格式：JPG格式（保证网页加载速度）

2. **保存照片到正确位置**
   - 将照片重命名为：`profile-photo.jpg`
   - 将照片保存到以下目录：
     ```
     /Users/chunyanwang/项目开发/个人网页/images/
     ```
   - Mac操作系统中，您可以通过按下Command+Shift+G并输入上述路径来快速导航到该目录

3. **验证照片显示正确**
   - 使用浏览器打开以下文件来预览您的网站：
     ```
     /Users/chunyanwang/项目开发/个人网页/index.html
     ```
   - 检查您的照片是否正确显示在网站顶部

4. **将更改提交到GitHub**
   - 打开终端应用
   - 导航到您的项目目录：
     ```
     cd /Users/chunyanwang/项目开发/个人网页
     ```
   - 添加照片文件到Git：
     ```
     git add images/profile-photo.jpg
     ```
   - 提交更改：
     ```
     git commit -m "Add professional profile photo"
     ```
   - 推送到GitHub：
     ```
     git push origin main
     ```

5. **查看在线网站**
   - 等待几分钟（GitHub Pages更新需要时间）
   - 访问您的网站查看更改：
     ```
     https://christy-wang98.github.io
     ```

## 常见问题解决

如果您的照片没有显示：

1. **检查文件名称和位置**
   - 确保文件名是：`profile-photo.jpg`（区分大小写）
   - 确保它位于`images`目录中

2. **检查文件格式**
   - 确保文件是有效的JPG格式

3. **推送问题**
   - 如果遇到推送错误，可以尝试先拉取：
     ```
     git pull origin main
     ```
   - 然后再次推送：
     ```
     git push origin main
     ```

如需进一步帮助，请随时联系！ 