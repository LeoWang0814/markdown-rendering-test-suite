# Markdown Full Feature Test Document

> This is a **Markdown rendering test file**  
> Designed to verify whether your system correctly parses and renders Markdown.

---

## 1. Text and Emphasis

This is a normal paragraph used to test basic text rendering.

- **Bold text**
- *Italic text*
- ***Bold and italic***
- ~~Strikethrough text~~
- `Inline code`

---

## 2. Heading Levels

# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6

---

## 3. Lists

### Unordered List
- Apple
- Banana
  - Sub item A
  - Sub item B
    - Nested sub item

### Ordered List
1. Step one
2. Step two
3. Step three

### Task List (GitHub Flavored Markdown)
- [x] Completed task
- [ ] Incomplete task
- [ ] Pending task

---

## 4. Blockquotes

> First-level quote  
>> Second-level quote  
>>> Third-level quote

---

## 5. Code Blocks

### Plain Code Block
```

This is a plain code block.
Line 2
Line 3

````

### Syntax Highlighting (Python)
```python
def hello(name):
    print(f"Hello, {name}!")

hello("Markdown")
````

### Syntax Highlighting (JavaScript)

```javascript
const greet = (name) => {
  console.log(`Hello, ${name}`);
};

greet("World");
```

---

## 6. Tables

| Name     | Type            | Status |
| -------- | --------------- | ------ |
| Markdown | Markup Language | ✅      |
| HTML     | Markup Language | ✅      |
| JSON     | Data Format     | ⚠️     |

Alignment test:

| Left | Center | Right |
| :--- | :----: | ----: |
| A    |    B   |     C |
| 1    |    2   |     3 |

---

## 7. Links

* Plain URL: [https://example.com](https://example.com)
* Markdown link: [GitHub](https://github.com)
* Link with title: [OpenAI](https://openai.com "OpenAI official website")

---

## 8. Image Test (External Hosting)

The image below is hosted on an external image service
to test HTTPS loading and Markdown image rendering:

![Markdown Image Test](https://youke2.picui.cn/s1/2025/12/22/694936dca528e.jpg)

---

## 9. Horizontal Rules

---

---

---

---

## 10. Footnotes (If Supported)

This sentence contains a footnote reference. [^1]

[^1]: This is the footnote content used to test extended Markdown syntax.

---

## 11. HTML and Markdown Mixed Rendering

<div style="padding: 12px; border: 1px solid #ccc; border-radius: 6px;">
  <strong>HTML Block:</strong>
  <p>
    If your renderer supports mixed HTML and Markdown,
    this section should display correctly.
  </p>
</div>

---

## 12. Escaped Characters

* Asterisk
_ Underscore
# Hash
> Greater-than symbol

---

## 13. Final Notes

If you can correctly see:

* Heading hierarchy
* Syntax-highlighted code blocks
* Properly aligned tables
* Rendered task lists
* External images
* Embedded HTML blocks

Then your Markdown renderer is **fully functional and production-ready** ✅
