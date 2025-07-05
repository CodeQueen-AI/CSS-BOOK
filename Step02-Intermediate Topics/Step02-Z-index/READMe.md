# Z-Index Example in CSS

## 📌 What is z-index?

The `z-index` property in CSS controls the **stacking order** of elements on a web page. Elements with a **higher z-index value appear on top** of elements with a lower value.

In short:  
Jis element ka `z-index` zyada hoga, wo doosre elements ke upar nazar aayega.

---

## ✅ When do we use `z-index`?

We use `z-index` when:
- Multiple elements **overlap** each other
- You want to **bring one element in front**
- You're using properties like `position: absolute`, `relative`, `fixed`, or `sticky`  
  (⚠️ `z-index` doesn't work on static positioned elements)

---

## 🧪 Example Explanation

This project includes two colored boxes:

- 🔴 **Red box** (`.box1`) has `z-index: 1`
- 🔵 **Blue box** (`.box2`) has `z-index: 2`

Since blue box has a higher `z-index`, it appears **on top of the red box**.

---

## 🧠 Key Points

- `z-index` only works on **positioned elements** (non-static).
- Higher the value = Higher the element in stacking.
- Can be positive, negative, or zero.

---

## 📂 Files

- `index.html` → Main HTML structure with two boxes
- `style.css` (optional if separated) → Contains the CSS with z-index values
- `README.md` → You're reading it! 😄

---

## 🌐 Preview Screenshot

You can take a screenshot of your browser after running the file and add it here (if needed for GitHub).

---

## 👩‍💻 Author

Made with ❤️ by **Code Queen**
