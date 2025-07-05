Wah Code Queen! 👑
Tum CSS ki **magic tricks** seekhne ke bilkul kareeb ho — ab baari hai **pseudo-elements** ki!
Specifically: `::before` aur `::after` — ye tumhare elements ke andar **extra invisible content** add karne ki power dete hain — bina HTML change kiye!

---

## 💡 One-Line Definition

### 🔸 `::before` & `::after`:

They let you **insert content before or after** an element’s actual content using CSS only.

📌 **Urdu:** Ye properties kisi bhi element ke **pehle ya baad virtual content** dikhane ke liye use hoti hain — bina HTML ko touch kiye!

---

## 🧪 Example Code (HTML + CSS)

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    .label::before {
      content: "🔥 ";
      color: red;
    }

    .label::after {
      content: " ✅";
      color: green;
    }
  </style>
</head>
<body>

  <p class="label">CSS is fun</p>

</body>
</html>
```

### ✅ Output:

The paragraph will look like:
**🔥 CSS is fun ✅**

---

## 🧠 Important Notes:

| Rule                          | Explanation                                         |
| ----------------------------- | --------------------------------------------------- |
| `content`                     | Required! Ye batata hai kya show karna hai          |
| Can’t target `input` directly | Only elements with content (like `<p>`, `<div>`)    |
| Styling allowed               | You can style the inserted content like normal text |

---

## 📄 README.md for Pseudo-elements

````markdown
# CSS Pseudo-elements (`::before` and `::after`)

## 💡 What are Pseudo-elements?

Pseudo-elements allow you to insert **virtual content** before or after an element's actual content using CSS only.

📌 Urdu: Ye CSS ka feature tumhein HTML element ke andar **extra text, icon ya design** add karne deta hai — bina HTML change kiye!

---

## 🔹 Syntax:

```css
.selector::before {
  content: "Text";
}
.selector::after {
  content: "Text";
}
````

The `content` property is **required**.

---

## 🧪 Example Description

```html
<p class="label">CSS is fun</p>
```

```css
.label::before {
  content: "🔥 ";
  color: red;
}
.label::after {
  content: " ✅";
  color: green;
}
```

### ✅ Output:

🔥 CSS is fun ✅

---

## ✅ Use Cases

* Add symbols or icons before/after text
* Decorative elements (like quotes, bullets, dividers)
* Tooltips, buttons, or ribbons

---

## 🧠 Pro Tips

* You can style them with `color`, `font-size`, `position`, etc.
* You can’t use them inside empty elements like `<input />`
* Always include the `content` property, even if it’s empty (`""`)

---

## 👩‍💻 Author

Styled like a queen 👑 by **Code Queen**

```

---

Agar chaho to me `::before` aur `::after` ke sath **animated ribbons**, **tooltip badges**, ya even **loading spinners** banake dikha sakti ho! 🎯

Batao next design magic kya ho? 💫💻
```
