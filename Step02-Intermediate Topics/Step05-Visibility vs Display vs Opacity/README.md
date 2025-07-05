Wah Code Queen! 👑
Yeh CSS ke **teen important properties** — `visibility`, `display`, aur `opacity` — beginners ko confuse karte hain. Chalo in teeno ko **side-by-side**, **simple explanation**, **comparison table**, **coding example**, aur ek perfect **README.md** ke sath samajhte hain!

---

## 🔍 One-Line Definitions:

| Property     | Definition (English + Urdu)                                                                                                                               |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `display`    | Controls **whether an element is rendered** and **takes space**. <br>Urdu: element ko **screen se hata deta hai**, aur uski **space bhi chhup jati hai**. |
| `visibility` | Controls **whether an element is visible**, but it still takes space. <br>Urdu: element **nazar nahi aata**, lekin **jagah rakhta hai**.                  |
| `opacity`    | Controls the **transparency level**. <br>Urdu: element **bilkul transparent ho jata hai**, lekin still clickable & in place.                              |

---

## 🧪 Example Code: HTML + CSS

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    .box {
      width: 150px;
      height: 100px;
      background-color: orange;
      margin: 10px;
      color: white;
      text-align: center;
      line-height: 100px;
      font-weight: bold;
    }

    .display-none {
      display: none;
    }

    .visibility-hidden {
      visibility: hidden;
    }

    .opacity-zero {
      opacity: 0;
    }
  </style>
</head>
<body>

  <div class="box">Normal</div>
  <div class="box display-none">Display: none</div>
  <div class="box visibility-hidden">Visibility: hidden</div>
  <div class="box opacity-zero">Opacity: 0</div>

</body>
</html>
```

---

## 📊 Comparison Table:

| Feature         | `display: none` | `visibility: hidden` | `opacity: 0` |
| --------------- | --------------- | -------------------- | ------------ |
| 👀 Visible?     | ❌ No            | ❌ No                 | ❌ No         |
| 📦 Space Taken? | ❌ No            | ✅ Yes                | ✅ Yes        |
| 🖱️ Clickable?  | ❌ No            | ❌ No                 | ✅ Yes        |
| 🔁 Reversible?  | ✅ Yes           | ✅ Yes                | ✅ Yes        |

---

## 📄 README.md

```markdown
# CSS Visibility vs Display vs Opacity

This project demonstrates the differences between three important CSS properties: `display`, `visibility`, and `opacity`.

---

## ✅ Definitions

- **display: none**  
  Completely removes the element from the document layout.  
  📌 Urdu: Element screen se **gayab ho jata hai** aur uski **space bhi nahi hoti**.

- **visibility: hidden**  
  Hides the element but **retains its space** in layout.  
  📌 Urdu: Element **nazar nahi aata**, lekin **space rakhta hai**.

- **opacity: 0**  
  Makes the element fully transparent (invisible), but **clickable** and **space is retained**.  
  📌 Urdu: Element **bilkul transparent ho jata hai**, lekin screen par hi hota hai.

---

## 🔍 Comparison Table

| Feature        | display: none | visibility: hidden | opacity: 0 |
|----------------|----------------|----------------------|-------------|
| Is visible?    | ❌ No           | ❌ No                 | ❌ No        |
| Takes space?   | ❌ No           | ✅ Yes                | ✅ Yes       |
| Clickable?     | ❌ No           | ❌ No                 | ✅ Yes       |

---

## 🧪 How to Test

Open `index.html` in a browser. You will see:
- One normal visible box
- One box missing (`display: none`)
- One hidden box space (`visibility: hidden`)
- One transparent box (`opacity: 0`) still takes space

---

## 👩‍💻 Author

Explained clearly by **Code Queen 👑**
```

---

Agar chaho to me isme ek **interactive toggle** button bhi bana sakti hoon jisse tum in properties ko on/off karke live dekh sakti ho.

Batao next step kya ho Code Queen? 💻✨
