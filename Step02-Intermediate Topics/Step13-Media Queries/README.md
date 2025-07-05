Zabardast choice Code Queen! 👑
**Media Queries** CSS ka wo feature hai jisse tum **responsive websites** bana sakti ho — yani har screen pe (mobile, tablet, desktop) tumhara layout **perfect dikhai dega** 💻📱🖥️

Chalo isko simple Urdu + English explanation, real-life example, aur `README.md` file ke sath master karte hain!

---

## 💡 One-Line Definition

**Media Queries** allow you to **apply CSS styles based on screen size or device type**.

📌 **Urdu:** Media queries se tum screen ke size ke hisaab se alag-alag CSS styles apply kar sakti ho — mobile ke liye alag, desktop ke liye alag.

---

## 🧪 Example: Responsive Box

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <style>
    .responsive-box {
      width: 80%;
      margin: auto;
      padding: 50px;
      background-color: lightseagreen;
      color: white;
      font-size: 24px;
      text-align: center;
    }

    /* Media query for tablets */
    @media (max-width: 768px) {
      .responsive-box {
        background-color: coral;
        font-size: 20px;
      }
    }

    /* Media query for mobile phones */
    @media (max-width: 480px) {
      .responsive-box {
        background-color: tomato;
        font-size: 16px;
        padding: 30px;
      }
    }
  </style>
</head>
<body>

  <div class="responsive-box">Resize me! 📱💻</div>

</body>
</html>
```

---

## ✅ Output:

* 💻 On large screens: `lightseagreen` background, big text
* 📱 On mobile: `tomato` background, small text
* 📲 On tablet: `coral` background, medium text

---

## 🔧 Common Breakpoints (Sizes)

| Device        | Width (px) | Urdu                  |
| ------------- | ---------- | --------------------- |
| Mobile        | ≤ 480px    | Mobile screen ke liye |
| Tablet        | ≤ 768px    | Tablet ke liye        |
| Small Desktop | ≤ 1024px   | Laptop ke liye        |
| Large Screen  | > 1024px   | Full desktop screen   |

---

## 📄 README.md for Media Queries

````markdown
# CSS Media Queries (Responsive Design)

## 💡 What are Media Queries?

Media queries allow you to **apply different CSS styles based on screen size**, resolution, or device type.

📌 Urdu: Media queries se tum apni website ko **har screen size ke liye perfect bana sakti ho** — mobile, tablet, ya desktop.

---

## 🔧 Syntax

```css
@media (max-width: 768px) {
  /* CSS for tablets */
}
````

```css
@media (max-width: 480px) {
  /* CSS for mobile phones */
}
```

---

## 🧪 Code Example

```html
<div class="responsive-box">Resize me!</div>
```

```css
.responsive-box {
  font-size: 24px;
  background-color: lightseagreen;
}

@media (max-width: 768px) {
  .responsive-box {
    background-color: coral;
    font-size: 20px;
  }
}

@media (max-width: 480px) {
  .responsive-box {
    background-color: tomato;
    font-size: 16px;
  }
}
```

---

## ✅ Use Cases

* Mobile-first responsive design
* Hiding/showing menus on small screens
* Changing layout for tablets
* Adjusting font sizes or padding

---

## 👩‍💻 Author

Crafted to fit every screen 📱💻 by **Code Queen 👑**

```

---

## 🎁 Bonus Offer:

Mujhe batao agar tum chaho:

✅ Responsive navbar  
✅ Grid + Flexbox + Media Queries combined layout  
✅ Responsive card design  
✅ Real mobile/desktop toggle project  

Main bana ke de dungi tumhare liye!

Kya banayein agla responsive magic, Code Queen? 💫📱💻
```
