Boht zabardast choice Code Queen! 👑
CSS **transitions** tumhari website ko **smooth animation effects** deti hain — bina kisi JavaScript ke!

Chalo isko easy language me samajhte hain step-by-step with:

✅ Simple definition
✅ Urdu explanation
✅ Code example
✅ Comparison table
✅ `README.md` file

---

## 💡 What is a CSS Transition?

### 🔸 One-line Definition:

`transition` property allows you to **smoothly animate changes** in CSS properties over time.

### 🔸 Urdu:

`transition` CSS me **slow aur smooth effects** create karta hai jab koi property (like color, size, position) change hoti hai.

---

## 🧪 Example Code: Smooth Hover Effect

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    .box {
      width: 150px;
      height: 150px;
      background-color: teal;
      transition: all 0.5s ease;
      color: white;
      text-align: center;
      line-height: 150px;
      font-weight: bold;
      font-size: 18px;
      margin: 20px;
    }

    .box:hover {
      background-color: tomato;
      width: 200px;
      height: 200px;
      font-size: 22px;
    }
  </style>
</head>
<body>

  <div class="box">Hover Me!</div>

</body>
</html>
```

---

## 🧠 Key Properties of Transition:

| Property                     | Meaning                                                  |
| ---------------------------- | -------------------------------------------------------- |
| `transition-property`        | Kis property par animation apply hogi (`color`, `width`) |
| `transition-duration`        | Animation kitni der chalegi (e.g. `0.5s`, `2s`)          |
| `transition-timing-function` | Animation ka speed pattern (`ease`, `linear`, etc.)      |
| `transition-delay`           | Animation start hone se pehle kitni der rukegi           |

---

## 📄 README.md for Transitions

````markdown
# CSS Transitions (Smooth Animation)

## 💡 What is a Transition?

A CSS transition allows you to change property values **smoothly** (over a duration), instead of instantly.

📌 Urdu: Jab koi style change hoti hai (jaise color ya size), to `transition` us change ko **slow aur smooth** banata hai — jhatka nahi deta!

---

## 🧪 Example Description

- A box with `transition: all 0.5s ease`
- On hover, it changes color, size, and font smoothly
- Without transition, these changes would be instant

---

## ✅ Syntax

```css
transition: [property] [duration] [timing-function] [delay];
````

### Example:

```css
transition: all 0.5s ease;
```

| Part   | Meaning                           |
| ------ | --------------------------------- |
| `all`  | Animate all properties            |
| `0.5s` | Animation duration = 0.5 seconds  |
| `ease` | Starts slow, speeds up, ends slow |

---

## 🔁 Use Cases

* Button hover effects
* Image zoom on hover
* Smooth menu opening
* Highlight form fields

---

## 👩‍💻 Author

Crafted with smoothness 🎨 by **Code Queen 👑**

```

---

Agar chaho to me `transition-delay`, `timing-function` variations, ya `transform` ke sath **animation effects** ka combo bhi bana ke de sakti hoon. 😎

Next kya explore karein? 💫
```
