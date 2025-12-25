# Markdown Rendering Test Suite

A comprehensive and carefully designed Markdown test repository  
for validating **Markdown parsers, renderers, and static site pipelines**.

一个用于测试 **Markdown 解析器、渲染器以及静态网站管线** 的完整示例集合。

---

## ✨ What is this?

This repository provides a **single, high-coverage Markdown file**  
that exercises most commonly used Markdown features, including:

- Basic and advanced syntax
- GitHub Flavored Markdown (GFM)
- Code blocks with language highlighting
- Tables, task lists, and footnotes
- External image loading
- HTML + Markdown mixed rendering

If your system renders this correctly,  
your Markdown support is already **production-ready**.

本仓库提供了一个**覆盖率极高的 Markdown 示例文件**，用于系统性测试：

- 基础与进阶 Markdown 语法
- GitHub 风格 Markdown（GFM）
- 代码高亮
- 表格 / 任务列表 / 脚注
- 外部图床图片加载
- HTML 与 Markdown 混合渲染

**如果你的页面能正确显示这个文件，  
你的 Markdown 支持已经非常可靠。**

---

## 📁 Repository Structure

```text
.
├── markdown-test.md     # Main Markdown test file
└── README.md            # Project documentation
````

---

## 🧪 What does it test?

The test file includes:

* Headings (H1–H6)
* Text emphasis (bold / italic / strikethrough)
* Ordered & unordered lists
* Nested blockquotes
* Inline code & fenced code blocks
* Syntax highlighting (Python / JavaScript)
* Tables with alignment
* Task lists (checkboxes)
* Links & external images
* Horizontal rules
* Footnotes (if supported)
* Escaped characters
* Embedded HTML blocks

---

## 🌐 Use Cases

This repository is useful if you are:

* Building a Markdown renderer
* Developing a static site generator
* Testing Markdown support in:

  * Cloudflare Pages / Workers
  * Vercel
  * GitHub Pages
  * Custom front-end frameworks
* Comparing different Markdown libraries:

  * `marked`
  * `markdown-it`
  * `remark`
  * `showdown`

---

## 🚀 How to use

1. Clone this repository:

   ```bash
   git clone https://github.com/LeoWang0814/markdown-rendering-test-suite.git
   ```

2. Open `markdown-test.md` in your system

3. Check whether all elements render as expected

4. Fix inconsistencies or unsupported features if needed

---

## 📸 External Image Test

The test file includes an externally hosted image to verify:

* HTTPS loading
* CORS behavior
* Image rendering inside Markdown

This helps catch real-world deployment issues early.

---

## 📄 License

MIT License.
Feel free to use, modify, and include this in your own projects.

---

## ⭐ Why this repo exists

Markdown looks simple — until it breaks.

This repository exists to help you **find those breaks early**,
before your users do.

---

If you find this useful, consider starring the repository ⭐
or using it as a baseline for your own Markdown tests.
