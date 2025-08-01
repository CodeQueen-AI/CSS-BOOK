# 🎯 CSS Borders and Outline

Borders and outlines are used to **visually highlight** elements like boxes, buttons, images, or text containers.

> 💬 Urdu: CSS mein borders aur outline ka use hota hai kisi element ko **highlight** ya **design** karne ke liye — jaise ke box ke ird gird line banana



## 🔹 What is `border`?

The `border` is a line drawn **around the edge** of an element

### ✨ Syntax:
`border: width style color;`

### 🧩 Examples of styles:
- `solid` → simple line  
- `dashed` → dotted lines  
- `dotted` → small dots  
- `double` → double line  

### 💬 Urdu:
**Border** element ke bilkul edge par line hoti hai — iska rang, style aur width set kiya ja sakta hai



## 🔸 `border-radius` – Rounded Corners

- Makes the corners **curved** instead of sharp.
- Example: `border-radius: 10px;`

💬 Urdu: Ye border ke kone gol banata hai



## 🔹 What is `outline`?

- `outline` is also a line **around the element**, but **outside** the border.
- Does **not** take space (no layout shift).
- Can be used for **focus highlight**, **error state**, etc.

💬 Urdu: Outline bhi ek line hoti hai jo element ke bahar hoti hai (border ke baad) — mostly focus ya hover pe use hoti hai.



## 🔸 `outline-offset`

- Creates **space between the border and the outline**.
- Example: `outline-offset: 10px;`

💬 Urdu: Outline aur border ke darmiyan gap deta hai.



## 🧾 Summary Table

| Property          | Description                                |    Meaning                         |
|-------------------|--------------------------------------------|--------------------------------------|
| `border`          | Line around element                       | Element ke gird line                 |
| `border-radius`   | Rounds the corners                        | Konon ko gol banata hai              |
| `outline`         | Extra line outside border                 | Border ke bahar wali line            |
| `outline-offset`  | Gap between border and outline            | Outline aur border ke darmiyan faasla |



## 💡 Use Cases

| Use This For              | Why?                            |
|---------------------------|---------------------------------|
| `border`                  | To give a visible edge          |
| `outline`                 | To highlight on focus or hover  |
| `border-radius`           | To make UI soft and modern      |
| `outline-offset`          | To separate outline visually    |

