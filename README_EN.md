# Personal Resume Display System

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-0.0.1-green.svg)]()

## 🌐 View Other Language Versions / 查看其他语言版本

- **English**: [README_EN.md](README_EN.md) (Current Document)
- **中文版**: [README.md](README.md)

---

## 📖 Project Description

A static personal resume display system based on HTML5, supporting Markdown format content with automatic translation from Chinese to English. No server required, runs directly in the browser.

## ✨ Key Features

### 🌐 Multi-language Support
- **Chinese Version**: Default display of Chinese resume content
- **English Version**: Automatic translation to English
- **URL Parameter Control**: Switch languages via `?lang=en`

### 📝 Markdown Support
- Uses `marked.js` to parse Markdown syntax
- Supports headings, lists, bold text, links, and other formats
- Automatically renders into beautiful HTML pages

### 🎨 Responsive Design
- Adapts to desktop, tablet, and mobile devices
- Modern UI design, clean and beautiful
- Supports dark/light themes

### ⚡ Static Deployment
- Pure frontend implementation, no backend service required
- Supports GitHub Pages, Vercel, and other platforms
- Fast loading, excellent performance

## 🚀 Quick Start

### 1. Clone Project
```bash
git clone https://github.com/yourusername/resume-display.git
cd resume-display
```

### 2. Edit Resume Content
Modify the `resume.md` file using Markdown syntax to write your resume:

```markdown
# Your Name | Position
**Phone**: Your phone number  
**Email**: Your email address  
**Work Experience**: X years

## Basic Information
- **Name**: Your name
- **Age**: Your age
- **Job Intention**: Desired position

## Work Experience
### Company Name - Job Title (Time Period)
- Responsible for specific work content
- Participated in project development
```

### 3. Local Preview
Open the `index.html` file directly in your browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

### 4. Deploy Online
Upload the project files to your hosting platform.

## 🌍 Language Switching

### Chinese Version
```
https://yourdomain.com/index.html
```

### English Version
```
https://yourdomain.com/index.html?lang=en
```

## 🛠️ Tech Stack

- **Frontend Framework**: HTML5 + CSS3 + JavaScript (ES6+)
- **Markdown Parser**: marked.js
- **PDF Export**: html2pdf.js
- **Responsive Design**: CSS Grid + Flexbox
- **Browser Compatibility**: Chrome, Firefox, Safari, Edge

## ⚙️ Configuration

### Custom Styling
Modify CSS styles in the `<style>` tag of `index.html`:

```css
/* Modify theme colors */
:root {
  --primary-color: #3b82f6;
  --secondary-color: #1e40af;
  --background-color: #f8fafc;
}

/* Modify fonts */
body {
  font-family: 'Your Font', sans-serif;
}
```

### Add New Features
Add JavaScript code in the `<script>` tag of `index.html`:

```javascript
// Add new button functionality
function customFunction() {
  // Your custom functionality
  console.log('Custom function executed');
}
```

## 📱 Responsive Breakpoints

- **Desktop**: > 1000px
- **Tablet**: 768px - 1000px  
- **Mobile**: < 768px

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [marked.js](https://marked.js.org/) - Markdown parser
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) - PDF export library

---

⭐ If this project helps you, please give it a star!
