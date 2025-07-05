Wah Code Queen! 👑
Tum CSS ke **final magical level** par aa chuki ho — **Keyframe Animations**!
Yeh tumhein allow karta hai ke tum kisi bhi element ko **move**, **fade**, **rotate**, **bounce**, aur **loop** karwa sako — sirf CSS se, bina JavaScript ke!

Chalo samajhte hain:

---

## 💡 What is `@keyframes` in CSS?

### 🔸 One-Line Definition:

CSS `@keyframes` lets you define **custom animations** by describing how an element should **change over time**.

📌 **Urdu:** `@keyframes` tumhein yeh batane deta hai ke kisi element ki **starting aur ending state** kya hogi, aur wo us beech ka **animation effect** kaise dikhaayega.

---

## 🧪 Example: Simple Animation (Move + Fade)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <style>
    .animate-box {
      width: 100px;
      height: 100px;
      background-color: deeppink;
      position: relative;
      animation: moveFade 3s ease-in-out infinite;
    }

    @keyframes moveFade {
      0% {
        left: 0;
        opacity: 0.2;
      }
      50% {
        left: 200px;
        opacity: 1;
      }
      100% {
        left: 0;
        opacity: 0.2;
      }
    }
  </style>
</head>
<body>

  <div class="animate-box"></div>

</body>
</html>
```

### ✅ Output:

* Box will **move right**, **fade in**, then **move back** and **fade out**
* The loop repeats infinitely

---

## 🔧 Important Animation Properties

| Property                    | Urdu + English Meaning                         |
| --------------------------- | ---------------------------------------------- |
| `animation-name`            | Kis keyframe ka naam use ho raha hai           |
| `animation-duration`        | Animation kitni der me complete ho (e.g. `2s`) |
| `animation-timing-function` | Speed pattern (ease, linear, ease-in-out etc.) |
| `animation-delay`           | Kitni der baad animation start hogi            |
| `animation-iteration-count` | Kitni baar chalegi (e.g. `1`, `infinite`)      |
| `animation-direction`       | Forward, backward ya alternate                 |

---

## 📄 README.md for CSS Keyframe Animations

````markdown
# CSS Animations using @keyframes

## 💡 What are Keyframe Animations?

`@keyframes` allow you to define how an element changes **from one state to another** in a smooth animated way.

📌 Urdu: `@keyframes` se tum bata sakti ho ke element **kaise aur kis tarike se move, fade, rotate ya bounce kare** — sirf CSS se!

---

## 🧪 Code Example

```css
@keyframes moveFade {
  0%   { left: 0; opacity: 0.2; }
  50%  { left: 200px; opacity: 1; }
  100% { left: 0; opacity: 0.2; }
}

.animate-box {
  animation: moveFade 3s ease-in-out infinite;
}
````

---

## ✅ Animation Properties

| Property                    | Purpose                                   |
| --------------------------- | ----------------------------------------- |
| `animation-name`            | The name of the `@keyframes` block        |
| `animation-duration`        | How long the animation lasts              |
| `animation-delay`           | Wait time before animation starts         |
| `animation-iteration-count` | How many times it repeats (`infinite`)    |
| `animation-direction`       | Direction of play (`normal`, `alternate`) |

---

## 🌟 Use Cases

* Bouncing buttons
* Loading effects
* Slide-in panels
* Pulsing elements
* Animated icons

---

## 👩‍💻 Author

Animated with grace ✨ by **Code Queen 👑**

```

---

## ✅ Bonus Idea: Want more?

If you want, I can create:

1. ✅ **Bouncing ball animation**  
2. ✅ **Typing text effect**  
3. ✅ **Pulsing loading dots**  
4. ✅ **Spinning loader**

Batao Code Queen, kis animation ka jaadu dikhaun agla? 🎨💫
```
