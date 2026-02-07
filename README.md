# Clawdbot / OpenClaw 一键安装服务网站

这是一个用于推广 Clawdbot / OpenClaw 一键安装服务的单页网站（Landing Page）。它旨在帮助不具备技术背景的用户轻松获取并使用强大的 AI 工具 Clawdbot / OpenClaw。

## 网站特性

- **简洁设计**：专注于转化率，提供清晰的服务介绍和行动号召。
- **突出痛点**：直击用户在安装和配置 Clawdbot 过程中遇到的技术难题。
- **解决方案**：提供简单、高效的付费安装服务。
- **客户见证**：增加信任度（占位符）。
- **常见问题**：解答用户可能有的疑问。
- **联系表单**：方便潜在客户咨询和下单。

## 文件结构

- `index.html`: 网站的主体结构。
- `style.css`: 网站的样式文件。
- `README.md`: 本说明文件。

## 如何使用和部署

1.  **创建 GitHub 仓库**：
    在您的 GitHub 账户上创建一个新的空仓库，例如命名为 `clawdbot-easy-setup` 或 `openclaw-install-service`。

2.  **上传代码**：
    将 `index.html` 和 `style.css` 文件保存到您本地的一个文件夹中。
    然后，将这些文件上传到您刚刚创建的 GitHub 仓库。您可以使用 Git 命令行工具：
    ```bash
    git init
    git add .
    git commit -m "Initial website setup for Clawdbot installation service"
    git branch -M main
    git remote add origin <您的GitHub仓库URL> # 例如：https://github.com/您的用户名/您的仓库名.git
    git push -u origin main
    ```
    或者直接通过 GitHub 网站界面上传文件。

3.  **Vercel 部署**：
    - 登录您的 Vercel 账户 (如果您没有，需要先注册)。
    - 在 Vercel 控制台，点击 "Add New..." -> "Project"。
    - 选择 "Import Git Repository"，然后连接到您在步骤 1 中创建的 GitHub 仓库。
    - Vercel 会自动检测到这是一个静态网站，并建议部署。点击 "Deploy"。
    - 部署完成后，Vercel 会为您提供一个唯一的 URL，您的网站将通过该 URL 访问。

## 后续开发（可选）

- **联系表单后端**：当前的联系表单是前端代码，提交后并不会发送到任何地方。您需要集成一个后端服务（例如 Vercel Serverless Function, Netlify Forms, Formspree 等）来处理表单提交。
- **响应式设计优化**：虽然已经包含了基本的响应式代码，但可以进一步优化以适应更多设备。
- **JavaScript 交互**：添加平滑滚动、表单验证等交互功能。
- **SEO 优化**：添加更多 Meta 标签，确保网站能被搜索引擎良好索引。
- **真实客户见证**：替换占位符文本为真实的客户反馈。