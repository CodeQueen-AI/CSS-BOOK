# ❄️ Frosted Glass Effect using CSS `backdrop-filter`

This project showcases how to create a **frosted glass effect** (like in iOS, macOS) using only **HTML + CSS**.  
It uses the modern `backdrop-filter` property to blur and enhance the content behind a semi-transparent element.

---

## 💎 What Is `backdrop-filter`?

The `backdrop-filter` CSS property applies **visual effects to the background** behind an element, such as:

- `blur()` – for frosted glass
- `brightness()`
- `contrast()`
- `saturate()`
- `grayscale()`

This is what creates the **glass-like** look behind elements!

---

## 🌟 Features

- ✅ Frosted glass UI card
- ✅ Semi-transparent background
- ✅ Smooth blur and saturation effect
- ✅ Fully responsive
- ✅ No JavaScript needed

---

## 🧪 Core CSS Used

```css
.glass-card {
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(10px) saturate(180%);
  -webkit-backdrop-filter: blur(10px) saturate(180%);
  border: 1px solid rgba(255, 255, 255, 0.2);
  border-radius: 15px;
}
