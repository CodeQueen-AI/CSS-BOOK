Yeh hui baat Code Queen! 👑
**CSS Pseudo-classes** ek **bohot powerful feature** hain — ye tumhein allow karte hain ke **element ki special states ya position** pe styling apply kar sako — bina kisi extra class ke!

Aaj hum focus karenge 3 super useful pseudo-classes pe:
✨ `:hover`, `:first-child`, `:nth-child()` — with **simple explanation**, **examples**, and a perfect **README.md** file.

---

## 💡 One-Line Definitions

| Pseudo-class    | Meaning (English + Urdu)                                                                                                           |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| `:hover`        | Applies styles **when you hover** your mouse over an element. <br>📌 Urdu: Jab cursor kisi element pe jata hai to style lagti hai. |
| `:first-child`  | Targets the **first child** of a parent element. <br>📌 Urdu: Sirf pehla element style hota hai.                                   |
| `:nth-child(n)` | Targets the **nth number** of child elements. <br>📌 Urdu: Kisi bhi specific number wale child pe styling lagti hai.               |

---

## 🧪 HTML + CSS Example

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    /* Hover effect */
    button:hover {
      background-color: green;
      color: white;
    }

    /* First child */
    ul li:first-child {
      color: red;
      font-weight: bold;
    }

    /* Nth child */
    ul li:nth-child(3) {
      color: blue;
      font-style: italic;
    }
  </style>
</head>
<body>

  <button>Hover Over Me</button>

  <ul>
    <li>First Item</li>
    <li>Second Item</li>
    <li>Third Item</li>
    <li>Fourth Item</li>
  </ul>

</body>
</html>
```

---

## 📄 README.md for Pseudo-classes

````markdown
# CSS Pseudo-classes (`:hover`, `:first-child`, `:nth-child()`)

## 💡 What are Pseudo-classes?

Pseudo-classes in CSS are used to define a special state or position of an element — like hover, first, or specific child.

📌 Urdu: Pseudo-classes kisi element ke **khaas halat** (jaise cursor aana, ya pehla/teesra item hona) par style lagati hain — bina class diye.

---

## 🔹 1. `:hover`

Applies style when the user moves the mouse over an element.

```css
button:hover {
  background-color: green;
  color: white;
}
````

🟢 Urdu: Jab mouse kisi button pe le jaayein to uska rang change ho jaye.

---

## 🔹 2. `:first-child`

Selects the first child element of a parent.

```css
ul li:first-child {
  color: red;
}
```

🟥 Urdu: Pehla `<li>` item red color me dikhai dega.

---

## 🔹 3. `:nth-child(n)`

Selects the **nth child** (like 2nd, 3rd, etc.).

```css
ul li:nth-child(3) {
  color: blue;
}
```

🔵 Urdu: Teesra item blue aur italic style me hoga.

---

## 🧪 Demo Summary

* A button that changes color on hover
* A list where:

  * First item is red
  * Third item is blue and italic

---

## 👩‍💻 Author

Styled with love 💖 by **Code Queen 👑**

```

---

### ✅ Extra Tip (Bonus):
Tum `:hover` ke saath `transform` aur `transition` bhi mila sakti ho for **animated hover effects** like scaling or rotating!

Agar chaho to me pseudo-classes ka **practice set** ya **real-life project** idea bhi de sakti hoon.  
Next kya explore karein Code Queen? 💅💻
```
