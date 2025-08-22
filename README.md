# 个人简历展示系统

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-0.0.1-green.svg)]()

## 🌐 查看其他语言版本 / View Other Language Versions

- **中文版**: [README.md](README.md) (当前文档)
- **English**: [README_EN.md](README_EN.md)

---

## 📖 项目简介

一个基于HTML5的静态个人简历展示系统，支持Markdown格式内容，具备自动将中文内容翻译为英文。无需服务器，可直接在浏览器中运行。

## ✨ 主要功能

### 🌐 多语言支持
- **中文版**: 默认显示中文简历内容
- **英文版**: 自动翻译为英文版本
- **URL参数控制**: 通过 `?lang=en` 切换语言

### 📝 Markdown支持
- 使用 `marked.js` 解析Markdown语法
- 支持标题、列表、粗体、链接等格式
- 自动渲染为美观的HTML页面

### 🎨 响应式设计
- 适配桌面、平板、手机等设备
- 现代化UI设计，简洁美观
- 支持深色/浅色主题

### ⚡ 静态部署
- 纯前端实现，无需后端服务
- 支持GitHub Pages、Vercel等平台
- 快速加载，性能优异

## 🚀 快速开始

### 1. 克隆项目
```bash
git clone https://github.com/yourusername/resume-display.git
cd resume-display
```

### 2. 编辑简历内容
修改 `resume.md` 文件，使用Markdown语法编写你的简历：

```markdown
# 你的姓名 | 职位
**电话**: 你的电话号码  
**邮箱**: 你的邮箱地址  
**工作经验**: X年

## 基本信息
- **姓名**: 你的姓名
- **年龄**: 你的年龄
- **求职意向**: 期望职位

## 工作经验
### 公司名称 - 职位名称 (时间段)
- 负责具体工作内容
- 参与项目开发
```

### 3. 本地预览
直接在浏览器中打开 `index.html` 文件，或使用本地服务器：

```bash
# 使用Python
python -m http.server 8000

# 使用Node.js
npx serve .

# 使用PHP
php -S localhost:8000
```

### 4. 部署上线
将项目文件上传到你的托管平台即可。

## 🌍 语言切换

### 中文版本
```
https://yourdomain.com/index.html
```

### 英文版本
```
https://yourdomain.com/index.html?lang=en
```

## 🛠️ 技术栈

- **前端框架**: HTML5 + CSS3 + JavaScript (ES6+)
- **Markdown解析**: marked.js
- **PDF导出**: html2pdf.js
- **响应式设计**: CSS Grid + Flexbox
- **浏览器兼容**: Chrome, Firefox, Safari, Edge

## ⚙️ 配置说明

### 自定义样式
在 `index.html` 的 `<style>` 标签中修改CSS样式：

```css
/* 修改主题色彩 */
:root {
  --primary-color: #3b82f6;
  --secondary-color: #1e40af;
  --background-color: #f8fafc;
}

/* 修改字体 */
body {
  font-family: 'Your Font', sans-serif;
}
```

### 添加新功能
在 `index.html` 的 `<script>` 标签中添加JavaScript代码：

```javascript
// 添加新的按钮功能
function customFunction() {
  // 你的自定义功能
  console.log('Custom function executed');
}
```

## 📱 响应式断点

- **桌面端**: > 1000px
- **平板端**: 768px - 1000px  
- **手机端**: < 768px

## 🔧 浏览器支持

| 浏览器 | 版本要求 | 支持状态 |
|--------|----------|----------|
| Chrome | 60+ | ✅ 完全支持 |
| Firefox | 55+ | ✅ 完全支持 |
| Safari | 12+ | ✅ 完全支持 |
| Edge | 79+ | ✅ 完全支持 |

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 🙏 致谢

- [marked.js](https://marked.js.org/) - Markdown解析器
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) - PDF导出库

---

⭐ 如果这个项目对你有帮助，请给它一个星标！
