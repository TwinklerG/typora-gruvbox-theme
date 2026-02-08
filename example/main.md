# Gruvbox Theme Preview

This document showcases all Markdown elements to help you preview the **Gruvbox theme** for Typora.

---

## 1. Headings

# H1 Heading
## H2 Heading
### H3 Heading
#### H4 Heading
##### H5 Heading
###### H6 Heading

---

## 2. Text Formatting

This is a regular paragraph with **bold text**, *italic text*, and ~~strikethrough text~~.

You can also use <mark>highlighted text</mark> and `inline code`.

Here's a [link to Gruvbox repository](https://github.com/morhetz/gruvbox) and an auto-linked URL: https://github.com

**Bold and *italic* combination** works too!

---

## 3. Lists

### Unordered Lists

* First item
* Second item
* Third item
  * Nested item 1
  * Nested item 2
    * Deep nested item

Alternative markers:

- Dashed item
- Another dashed item
+ Plus item
+ Another plus item

### Ordered Lists

1. First item
2. Second item
3. Third item
   1. Nested item A
   2. Nested item B
4. Fourth item

### Task Lists

- [x] Completed task
- [x] Another completed task
- [ ] Incomplete task
- [ ] Another incomplete task with **bold text**

---

## 4. Blockquotes

> This is a blockquote. It can contain **bold text** and *italic text*.
> 
> Multiple paragraphs in a blockquote.

> Nested blockquotes:
>> This is a nested blockquote.
>> 
>> With multiple lines.

---

## 5. Code

### Inline Code

Use `console.log()` for debugging. The `gruvbox` theme has `beautiful` colors.

### Code Blocks

```python
# Python example
def greet(name):
    """This is a docstring"""
    message = f"Hello, {name}!"
    return message

# Function call
result = greet("World")
print(result)
```

```javascript
// JavaScript example
const gruvbox = {
    dark: '#282828',
    light: '#fbf1c7',
    red: '#cc241d',
    green: '#98971a',
    yellow: '#d79921',
    blue: '#458588',
    purple: '#b16286',
    aqua: '#689d6a',
    orange: '#d65d0e'
};

console.log(gruvbox.dark);
```

```css
/* CSS example */
.gruvbox-theme {
    background-color: #282828;
    color: #ebdbb2;
    font-family: 'Inconsolata', monospace;
}

.gruvbox-theme h1 {
    color: #fe8019;
}
```

---

## 6. Tables

| Feature | Dark Theme | Light Theme |
|:--------|:----------:|:-----------:|
| Background | `#282828` | `#fbf1c7` |
| Foreground | `#ebdbb2` | `#3c3836` |
| Red | `#fb4934` | `#9d0006` |
| Green | `#b8bb26` | `#79740e` |
| Yellow | `#fabd2f` | `#b57614` |
| Blue | `#83a598` | `#076678` |
| Purple | `#d3869b` | `#8f3f71` |
| Aqua | `#8ec07c` | `#427b58` |

---

## 7. Horizontal Rules

Above the line

---

Below the line

***

Alternative style

___

Another alternative

---

## 8. Math Blocks

Inline math: $E = mc^2$

Block math:

$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$

$$
\sum_{i=1}^{n} x_i = x_1 + x_2 + \cdots + x_n
$$

---

## 9. Footnotes

This is a sentence with a footnote[^1].

[^1]: This is the footnote content.

---

## 10. Images

![Gruvbox Logo](https://raw.githubusercontent.com/morhetz/gruvbox/master/gruvbox.png)

*Gruvbox color palette visualization*

---

## 11. Definition Lists

Term 1
:   Definition 1

Term 2
:   Definition 2a
:   Definition 2b

---

## 12. HTML Elements

<details>
<summary>Click to expand</summary>

This is hidden content that can be expanded.

- Item 1
- Item 2
- Item 3

</details>

---

## 13. Emoji (if supported)

:smile: :heart: :thumbsup: :rocket:

---

## 14. Comments

<!-- This is a HTML comment that won't be rendered -->

---

## 15. Metadata Block

---
title: Gruvbox Theme
date: 2026-02-08
author: Your Name
tags: [theme, gruvbox, typora]
---

This document demonstrates the **Gruvbox** theme's rendering of various Markdown elements. Enjoy the warm, retro groove colors!
