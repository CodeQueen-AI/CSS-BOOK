Wah Code Queen! 👑
Ab hum CSS ka ek aur **fun and powerful** concept seekhenge: **Transforms**!
Ye properties tumhein allow karti hain ke tum kisi bhi element ko **guma sako, bada/chhota kar sako, ya idhar-udhar move** kar sako — bilkul magic jaisa ✨

---

## 💡 What is `transform` in CSS?

### 🔸 One-line Definition:

`transform` property allows you to **rotate, scale, move, or skew** HTML elements.

### 🔸 Urdu:

`transform` kisi bhi element ko **ghumata (rotate)** hai, **size change karta (scale)** hai, ya **position change karta (translate)** hai.

---

## 🎯 Common Transform Functions:

| Function      | What it Does               | Urdu Explanation                         |
| ------------- | -------------------------- | ---------------------------------------- |
| `rotate()`    | Ghoomata hai (in degrees)  | Element ko angle ke sath **ghumata** hai |
| `scale()`     | Bada ya chhota karta hai   | Element ko **zoom in/out** karta hai     |
| `translate()` | Move karta hai (X, Y axis) | Element ko **idhar udhar** le jata hai   |

---

## 🧪 Example Code (HTML + CSS)

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    .box {
      width: 150px;
      height: 150px;
      background-color: purple;
      color: white;
      text-align: center;
      line-height: 150px;
      margin: 20px;
      font-weight: bold;
      transition: 0.5s ease;
    }

    .box:hover {
      transform: rotate(15deg) scale(1.2) translateX(30px);
    }
  </style>
</head>
<body>

  <div class="box">Hover Me!</div>

</body>
</html>
```

👆 Hover karne par box **ghoomega**, **bada hoga**, aur **right side move karega** — sab kuch ek sath!

---

## 📄 README.md for `transform`

````markdown
# CSS Transforms (rotate, scale, translate)

## 💡 What is `transform`?

The `transform` property in CSS lets you visually manipulate elements by **rotating**, **scaling**, **moving**, or **skewing** them.

📌 Urdu: CSS `transform` se hum kisi element ko **ghuma**, **bara/chhota**, ya **move** kar sakte hain — bilkul animation jaisa effect deta hai!

---

## ✨ Common Transform Functions

| Function     | Use Case                      |
|--------------|-------------------------------|
| `rotate(15deg)`  | Rotates the element by 15 degrees |
| `scale(1.2)`     | Makes the element 20% larger      |
| `translateX(30px)` | Moves the element 30px to the right |
| `translateY(-20px)` | Moves the element 20px upward |

---

## 🧪 Example Description

This demo includes:
- A purple box
- On hover: it rotates, grows in size, and shifts right

```css
transform: rotate(15deg) scale(1.2) translateX(30px);
````

---

## ✅ Combine with `transition`

To make transform effects **smooth**, use it with:

```css
transition: 0.5s ease;
```

---

## 🧠 Pro Tip

* You can combine multiple transforms together.
* Order matters: `rotate + scale + translate` ≠ `translate + rotate + scale`

---

## 👩‍💻 Author

Transformed with style 💅 by **Code Queen 👑**

```

---

Agar chaho to me **individual examples** for rotate, scale, translate bana ke bhi dikha sakti hoon ya isko ek animation project jaisa design bhi kar sakti hoon!  
Batao Code Queen, agla topic kya ho? 💖💻
```
