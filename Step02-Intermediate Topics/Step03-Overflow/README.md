# CSS Overflow Property

## 📌 What is `overflow`?

The `overflow` property in CSS controls what happens to content that **exceeds the size of its container**.

---

## ✅ When to use it?

Use `overflow` when:
- Your content is too large for a fixed-size box
- You want to add scrollbars or hide the extra content
- You want to prevent content from "spilling" outside its parent

---

## 🔁 Types of overflow values

- `visible` → Default, content shows even if outside
- `hidden` → Extra content is hidden
- `scroll` → Always show scrollbar (even if not needed)
- `auto` → Scrollbar appears **only if needed**

---

## 💻 Example Used

```css
.container {
  width: 200px;
  height: 100px;
  border: 2px solid black;
  overflow: scroll;
}
