# Clawdbot / OpenClaw 一键安装服务网站

这是一个用于推广 Clawdbot / OpenClaw 一键安装服务的单页网站（Landing Page）。它旨在帮助不具备技术背景的用户轻松获取并使用强大的 AI 工具 Clawdbot / OpenClaw。

## 🌟 网站特性

- **简洁设计**：专注于转化率，提供清晰的服务介绍和行动号召
- **突出痛点**：直击用户在安装和配置 Clawdbot 过程中遇到的技术难题
- **解决方案**：提供简单、高效的付费安装服务（299元/月）
- **真实案例**：展示多个用户的实际使用场景
- **客户见证**：增加信任度和说服力
- **常见问题**：解答用户可能有的疑问
- **准备指南**：详细说明使用前需要准备的内容
- **联系表单**：方便潜在客户咨询和下单

## 📁 文件结构

```
openclaw-install/
├── index.html          # 网站主体结构
├── style.css           # 网站样式文件
├── README.md           # 项目说明文档
├── article.md          # 开发经验分享文章
└── wechat-article.md   # 公众号推广文章
```

## 🎨 设计亮点

### 视觉设计
- 现代渐变色主题（紫色系）
- 流畅的动画效果（脉冲、浮动、弹跳）
- 精美的卡片布局和阴影效果
- 完全响应式设计，适配各种设备

### 功能模块
1. **Hero 区域** - 吸引眼球的标题和行动号召
2. **痛点分析** - 3个核心问题展示
3. **解决方案** - 服务特点和价格信息
4. **用户案例** - 6个真实使用场景
5. **客户评价** - 社会证明
6. **准备指南** - 使用前需要准备的内容
7. **FAQ** - 常见问题解答
8. **联系表单** - 带二维码的咨询入口

## 💰 服务定价

- **基础服务**：299元/月（首月特惠 249元）
- **一站式安装**：额外 99元（前50名免费）
- **技术支持**：30天免费支持

### 额外费用（用户自行承担）
- 云服务器：30-100元/月
- API 使用费：50-200元/月

## 🛠️ 技术栈

- **HTML5** - 语义化标签
- **CSS3** - 现代样式和动画
- **原生 JavaScript** - FAQ 交互功能
- **响应式设计** - 移动端优先

## 📋 使用前准备

用户需要准备以下内容：

1. **云服务器**
   - 推荐：腾讯云/阿里云
   - 或使用：[iKunYun](https://www.ikunyun.cn/aff/FQYOYHZM)

2. **飞书机器人密钥**
   - App ID 和 App Secret

3. **API Key**
   - 获取地址：https://apipro.maynor1024.live/

4. **远程工具**
   - ToDesk（推荐）或其他远程软件

## 🚀 快速开始

### 本地预览

1. 克隆仓库
```bash
git clone https://github.com/xianyu110/openclaw-install.git
cd openclaw-install
```

2. 打开 index.html
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

### 部署到 Vercel

1. Fork 本仓库到你的 GitHub 账号
2. 登录 [Vercel](https://vercel.com)
3. 点击 "New Project"
4. 导入你 Fork 的仓库
5. 点击 "Deploy"

### 部署到 GitHub Pages

1. 进入仓库 Settings
2. 找到 Pages 选项
3. Source 选择 main 分支
4. 保存后等待部署完成

## 📝 自定义修改

### 修改联系方式

编辑 `index.html` 中的联系信息：

```html
<!-- 修改邮箱 -->
<p class="contact-value">your-email@example.com</p>

<!-- 修改二维码 -->
<img src="你的二维码链接" alt="咨询二维码" class="qr-code">
```

### 修改价格

编辑 `index.html` 中的价格部分：

```html
<p class="price-value"><span class="currency">$</span>299</p>
```

### 修改颜色主题

编辑 `style.css` 中的渐变色：

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

## 📊 SEO 优化建议

- [ ] 添加 meta description
- [ ] 添加 Open Graph 标签
- [ ] 添加 Twitter Card 标签
- [ ] 优化图片 alt 属性
- [ ] 添加结构化数据（Schema.org）
- [ ] 提交到 Google Search Console

## 🔗 相关链接

- **在线演示**：[待部署]
- **GitHub 仓库**：https://github.com/xianyu110/openclaw-install
- **开发文章**：查看 `article.md`
- **推广文案**：查看 `wechat-article.md`

## 📄 许可证

MIT License

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📮 联系方式

如有问题或建议，请通过以下方式联系：

- 扫描网站二维码添加微信
- 发送邮件至：service@example.com

---

**由 Clawbot AI 辅助开发** 🤖
