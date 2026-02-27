# DocConvert Web

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Docker](https://img.shields.io/badge/docker-supported-green.svg)](docker-compose.yml)

> 文档转换 & OCR 识别工具 — 支持 Word、Excel、PPT、PDF 等多种格式互转，以及图片文字识别

[English](#english) | [中文](#中文)

---

## 中文

### 功能特性

- **📄 文档格式转换**
  - 支持 Word (DOCX)、Excel (XLSX)、PowerPoint (PPTX)、PDF、ODT、ODS 等多种格式
  - 拖拽上传，一键转换
  - 浏览器本地处理，无需上传服务器

- **🖼️ OCR 文字识别**
  - 识别图片中的文字
  - 支持 JPG、PNG、WEBP、GIF 等格式
  - 中英文混合识别

- **🔒 隐私保护**
  - 纯前端处理，文件不上传云端
  - 本地完成所有转换和识别操作

### 技术栈

- **前端**: HTML5, CSS3, JavaScript (原生)
- **后端代理**: Nginx
- **部署**: Docker, Docker Compose

### 快速开始

#### 方式一：Docker 部署（推荐）

```bash
# 克隆项目
git clone https://github.com/IVMYM/docconvert-web.git
cd docconvert-web

# 启动服务
docker-compose up -d

# 访问 http://localhost:8080
```

#### 方式二：直接使用

直接在浏览器中打开 `index.html` 即可使用基础功能。

### 文件结构

```
docconvert-web/
├── index.html          # 主应用文件
├── docker-compose.yml  # Docker 部署配置
├── nginx.conf          # Nginx 配置文件
└── README.md           # 项目说明
```

### 演示

访问在线演示：[https://conv.uyxzfu.eu.org/](https://conv.uyxzfu.eu.org/)

### 浏览器支持

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

---

## English

### Features

- **📄 Document Format Conversion**
  - Support Word (DOCX), Excel (XLSX), PowerPoint (PPTX), PDF, ODT, ODS, and more
  - Drag & drop upload, one-click conversion
  - Browser-based processing, no server upload required

- **🖼️ OCR Text Recognition**
  - Extract text from images
  - Support JPG, PNG, WEBP, GIF formats
  - Chinese & English mixed recognition

- **🔒 Privacy Protection**
  - Pure frontend processing, files never leave your device
  - All conversions and recognition done locally

### Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Reverse Proxy**: Nginx
- **Deployment**: Docker, Docker Compose

### Quick Start

#### Option 1: Docker Deployment (Recommended)

```bash
# Clone the repository
git clone https://github.com/IVMYM/docconvert-web.git
cd docconvert-web

# Start the service
docker-compose up -d

# Access at http://localhost:8080
```

#### Option 2: Direct Usage

Simply open `index.html` in your browser for basic functionality.

### File Structure

```
docconvert-web/
├── index.html          # Main application
├── docker-compose.yml  # Docker deployment config
├── nginx.conf          # Nginx configuration
└── README.md           # Project documentation
```

### Demo

Try it online: [https://conv.uyxzfu.eu.org/](https://conv.uyxzfu.eu.org/)

### Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

---

## 许可证 / License

MIT License © 2024 IVMYM

---

## 作者 / Author

- **GitHub**: [@IVMYM](https://github.com/IVMYM)
- **Email**: lyuan1618@gmail.com

如有问题或建议，欢迎提交 Issue 或 Pull Request！
