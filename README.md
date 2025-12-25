# Markdown Rendering Test Suite

A comprehensive and carefully designed Markdown test repository  
for validating **Markdown parsers, renderers, and static site pipelines**.

一个用于测试 **Markdown 解析器、渲染器以及静态网站管线** 的完整示例集合。

---

## 🌍 Language Versions Available

This repository provides **both Chinese and English versions** of the Markdown test file  
to support **internationalization (i18n) testing** and cross-language rendering comparison.

本仓库同时提供 **中文版与英文版 Markdown 测试文件**，  
适用于 **多语言渲染测试 / 国际化支持验证**。

| Language | File |
|--------|------|
| 中文版 (Chinese) | `markdown-test-zh.md` |
| English | `markdown-test-en.md` |

Both files are **functionally identical** and differ only in text language.  
两个文件在 **结构与测试覆盖范围上完全一致，仅文本语言不同**。

---

## ✨ What is this?

This repository provides a **high-coverage Markdown test file**  
that exercises most commonly used Markdown features, including:

- Basic and advanced syntax
- GitHub Flavored Markdown (GFM)
- Code blocks with language highlighting
- Tables, task lists, and footnotes
- External image loading
- HTML + Markdown mixed rendering

If your system renders these files correctly,  
your Markdown support is already **production-ready**.

本仓库提供了一个**覆盖率极高的 Markdown 示例文件**，用于系统性测试：

- 基础与进阶 Markdown 语法
- GitHub 风格 Markdown（GFM）
- 代码高亮
- 表格 / 任务列表 / 脚注
- 外部图床图片加载
- HTML 与 Markdown 混合渲染

**如果你的页面能正确显示这些测试文件，  
你的 Markdown 支持已经非常可靠。**

---

## 📁 Repository Structure

```text
.
├── markdown-test-zh.md   # 中文版 Markdown 测试文件
├── markdown-test-en.md   # English Markdown test file
└── README.md             # Project documentation
````

---

## 🧪 What does it test?

Each test file includes:

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
* Validating **multi-language Markdown rendering consistency**

---

## 🚀 How to use

1. Clone this repository:

   ```bash
   git clone https://github.com/LeoWang0814/markdown-rendering-test-suite.git
   ```

2. Open either test file:

   * `markdown-test-zh.md` for Chinese
   * `markdown-test-en.md` for English

3. Render the file in your system

4. Verify that all elements display as expected

5. Fix unsupported or inconsistent behaviors if needed

---

## 📸 External Image Test

Both test files include an externally hosted image to verify:

* HTTPS image loading
* CORS behavior
* Image rendering inside Markdown content

This helps identify real-world deployment issues early.

---

## 📄 License

MIT License.
Feel free to use, modify, and include this repository in your own projects.

---

## ⭐ Why this repo exists

Markdown looks simple — until it breaks.

This repository exists to help you **find rendering issues early**,
before they reach production or your users.

If you find this useful, consider starring the repository ⭐
or using it as a baseline for your own Markdown tests.
