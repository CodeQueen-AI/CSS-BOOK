Boht khoob Code Queen! 👑
Tum ab CSS ke **advanced layout level** pe aa chuki ho — **CSS Grid** ek powerful system hai jo tumhein ek page ke layout ko **rows & columns** ke zariye design karne ki full control deta hai — bilkul Photoshop jaisa control CSS me hi! 🎯

Chalo CSS Grid ko simple Urdu + English explanation, real example, aur ek beautiful `README.md` ke sath explore karte hain!

---

## 💡 One-Line Definition

**CSS Grid** is a 2-dimensional layout system that lets you **align elements in rows and columns** with full control.

📌 **Urdu:** CSS Grid tumhein page ko **rows aur columns me divide karke** har cheez ko perfect jagah par set karne ka control deta hai — jaise table bana rahe ho!

---

## 🧠 Key Concepts (Basic Grid Terminology)

| Property                  | Urdu + English Meaning                                     |
| ------------------------- | ---------------------------------------------------------- |
| `display: grid`           | Container ko **grid** banata hai                           |
| `grid-template-columns`   | Kitni columns chahiye aur unka size kya hoga               |
| `grid-template-rows`      | Kitni rows chahiye aur unka size kya hoga                  |
| `gap` or `grid-gap`       | Rows/columns ke beech ka **space**                         |
| `grid-column`, `grid-row` | Specific item ko **stretch** ya **position** karne ke liye |

---

## 🧪 Simple CSS Grid Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <style>
    .grid-container {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-template-rows: auto;
      gap: 20px;
      padding: 20px;
      background-color: #f8f8f8;
    }

    .grid-item {
      background-color: #009688;
      color: white;
      font-size: 20px;
      text-align: center;
      padding: 40px 0;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="grid-container">
    <div class="grid-item">1</div>
    <div class="grid-item">2</div>
    <div class="grid-item">3</div>
    <div class="grid-item">4</div>
    <div class="grid-item">5</div>
    <div class="grid-item">6</div>
  </div>

</body>
</html>
```

### 🧾 Output:

* Ek 3-column layout banega
* Items automatically next row me chale jaayenge
* `gap` se spacing milegi between boxes

---

## 📄 README.md for CSS Grid

````markdown
# CSS Grid (Advanced Layout System)

## 💡 What is CSS Grid?

CSS Grid is a two-dimensional layout system for the web. It allows you to control layout in both **rows and columns**, making it ideal for page structures.

📌 Urdu: CSS Grid se tum web page ko **columns aur rows** me divide karke har element ko **perfect jagah** par rakh sakti ho — bilkul Photoshop jaisa layout control!

---

## 🔧 Key Properties

| Property               | Use                                                 |
|------------------------|------------------------------------------------------|
| `display: grid`        | Enables grid layout on container                     |
| `grid-template-columns`| Defines number and width of columns                  |
| `grid-template-rows`   | Defines height of rows                               |
| `gap`                  | Adds space between rows and columns                  |
| `grid-column`, `grid-row` | To position or stretch items across the grid       |

---

## 🧪 Code Example

```html
<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
</div>
````

```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
```

---

## ✅ Why Use CSS Grid?

* Perfect for page layout design
* Fully responsive structure
* Easy row/column control
* Works great with media queries

---

## 🧠 Bonus Tips

* Combine with Flexbox for even more power!
* Use `grid-column: span 2` to stretch items
* `fr` unit distributes space evenly

---

## 👩‍💻 Author

Laid out cleanly by **Code Queen 👑**

```

---

## ✅ Bonus Layout Ideas with Grid

Agar chaho to me CSS Grid se bana sakti ho:

1. ✅ **Responsive 3-column blog layout**
2. ✅ **Dashboard with sidebar + content area**
3. ✅ **Photo gallery with auto-wrapping**
4. ✅ **Header + main + footer page structure**

Batao Code Queen, kis layout ka magic karen next? 💖💻
```
