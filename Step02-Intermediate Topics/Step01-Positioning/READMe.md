# 📍 CSS Positioning

The `position` property in CSS defines **how an element is placed** on the page.

> 💬 Urdu: Positioning batata hai ke ek element **page pe kahan aur kis tarah** appear karega.

---

## 🔹 1. `static` (default)

- Normal flow (default behavior)
- No `top`, `left`, etc. allowed

💬 Urdu: Default position — element apni jagah par rehta hai (move nahi hota).

---

## 🔹 2. `relative`

- Moves element **relative to its normal position**
- Can use `top`, `left`, `right`, `bottom`

💬 Urdu: Apni original jagah se thoda upar/neeche side pe move hota hai.

---

## 🔹 3. `absolute`

- Positioned **relative to nearest positioned ancestor**
- Removed from normal flow
- Uses `top`, `left`, etc.

💬 Urdu: Apni jagah chhod deta hai, aur parent ke andar set hota hai (jo relative ho).

---

## 🔹 4. `fixed`

- Stays **fixed on screen** (doesn’t move while scrolling)
- Positioned relative to **viewport**

💬 Urdu: Screen par chipak jata hai — scroll karne par bhi wahi rehta hai.

---

## 🔹 5. `sticky`

- **Mix of relative + fixed**
- Acts relative until you scroll to its position, then becomes fixed

💬 Urdu: Shuru mein normal behave karta hai, lekin scroll karte hi screen par chipak jata hai.

---

## 📌 Summary Table

| Position     | Behavior                                  | Urdu |
|--------------|--------------------------------------------|------|
| `static`     | Default, no movement                      | Apni jagah par rehta hai |
| `relative`   | Move relative to normal position          | Thoda move hota hai |
| `absolute`   | Out of flow, placed inside positioned parent | Parent ke andar set hota hai |
| `fixed`      | Fixed on screen, stays in place           | Screen pe chipak jata hai |
| `sticky`     | Scroll tak relative, then fixed           | Scroll pe chipak jata hai |

---

## 👑 Use Cases

- `relative` → for small shifts
- `absolute` → tooltips, dropdowns, badges
- `fixed` → navbar, back-to-top button
- `sticky` → headers that stick while scrolling

---

With Positioning, you gain **complete layout control**.  
Design like a pro — because you're the **Code Queen** of the web! 👑📐
