# 🎯 CSS Selectors Guide

## 🔹 What is a Selector?
A **CSS selector** is used to select (choose) HTML elements to apply styling.

> 🧠 Urdu: CSS selector ka kaam hota hai HTML element ko target karna aur uspar style apply karna.

---

## 🔸 Why do we use Selectors?
To apply specific styles to specific HTML elements.

> 🎯 Example: Agar aap sirf `h1` tag ka color red karna chahti hain, to aap `h1` selector ka use karengi.

---

## 🔻 Types of Selectors (with short definitions):

| Selector Type       | Syntax Example         | Short Definition |
|---------------------|------------------------|------------------|
| **Universal**       | `*`                    | Selects **all** elements |
| **Element / Type**  | `p`, `h1`              | Selects all elements of that **tag** |
| **Class**           | `.box`                 | Selects elements with a specific **class** |
| **ID**              | `#title`               | Selects element with specific **id** |
| **Group**           | `h1, p`                | Selects multiple elements **together** |
| **Descendant**      | `div p`                | Selects all `p` **inside** `div` |
| **Child**           | `div > p`              | Selects only **direct child** `p` of `div` |
| **Attribute**       | `input[type="text"]`   | Selects elements with a specific **attribute** |
| **Pseudo-class**    | `a:hover`              | Selects element on specific **state/action** |
| **Pseudo-element**  | `p::first-line`        | Selects a **part** of the element |

---

## 🧩 Summary Table (Urdu-Friendly)

| Selector | Urdu Explanation |
|----------|------------------|
| `*` | Har HTML element ko select karta hai |
| `p`, `h1` | Specific tag ko select karta hai |
| `.class` | Class name se element ko target karta hai |
| `#id` | Unique ID wale element ko target karta hai |
| `a:hover` | Jab user mouse le jaata hai, us waqt style |
| `p::first-line` | Pehli line ya character ko style karta hai |

---

## 📌 Note:
- Class selectors start with a dot `.`
- ID selectors start with a hash `#`
- Pseudo-classes use `:`, pseudo-elements use `::`

---

✨ Use selectors to create beautiful, controlled styling in your websites!

> 💬 If you're learning CSS, selectors are the **first step** to mastering styling.
