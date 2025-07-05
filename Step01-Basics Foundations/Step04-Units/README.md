# 📏 CSS Units Guide

CSS units define the size of elements like width, height, font-size, padding, etc.

> 💬 Urdu: CSS units ka use element ka size ya font-size set karne ke liye hota hai.

---

## 🔸 Common CSS Units with Short Definitions

| Unit | Example     | Description |
|------|-------------|-------------|
| `px` | `width: 100px;` | Fixed size in pixels (1px = 1 dot on screen) |
| `%`  | `width: 50%;`   | Relative to parent element |
| `em` | `font-size: 2em;` | Relative to **parent's** font size |
| `rem`| `font-size: 1.5rem;` | Relative to **root** (HTML) font size |
| `vh` | `height: 50vh;` | Relative to **viewport height** |
| `vw` | `width: 80vw;`  | Relative to **viewport width** |

---

## 📘 Example Code

```css
/* px - fixed value */
.box {
  width: 200px;
}

/* % - relative to parent */
.box {
  width: 50%;
}

/* em - relative to parent font-size */
.box {
  font-size: 2em;
}

/* rem - relative to root font-size */
.box {
  font-size: 1.5rem;
}

/* vh - 10% of screen height */
.box {
  height: 10vh;
}

/* vw - 50% of screen width */
.box {
  width: 50vw;
}
