# 📦 CSS Display Property

The `display` property in CSS controls **how an element appears on the page**.

> 💬 Urdu: Display property batati hai ke ek element **line ke sath ayega, alag block banega, ya chhup jaayega**.



## 🔹 1. `display: block`

- Each element **takes full width** (100% of the line)
- Starts on a **new line**
- Common for: `<div>`, `<p>`, `<h1>`, `<section>`

💬 Urdu: Har element **neeche naya line** start karta hai. Poora row le leta hai



## 🔹 2. `display: inline`

- Sits **in the same line**
- Takes **only the required width**
- Cannot set `width` or `height`
- Common for: `<span>`, `<a>`, `<strong>`

💬 Urdu: Yeh element **line ke sath sath** chalta hai — chhoti cheezon ke liye




## 🔹 3. `display: inline-block`

- **Behaves like inline**, but allows **width & height**
- Used when we want small boxes side by side

💬 Urdu: Line ke andar rehta hai **lekin box jaise behave karta hai**



## 🔹 4. `display: none`

- Completely **hides** the element from page
- **Doesn't take any space**
- Used to **hide/show** elements with JavaScript

💬 Urdu: Ye element ko **chhupa deta hai** — page par dikhayi nahi deta aur jagah bhi nahi leta.




## 📌 Summary Table (English + Urdu)

| Value           | Behavior                       |      Explanation                      |
|------------------|-------------------------------|----------------------------------------|
| `block`         | Full width, new line           | Poora line le kar neeche chala jata hai |
| `inline`        | Side by side, no height/width  | Line ke andar rehta hai, width fix nahi |
| `inline-block`  | Line ke andar + settable size  | Line mein rehta hai + height/width set hoti hai |
| `none`          | Completely hidden              | Element gayab ho jata hai, jagah bhi nahi leta |

## 🧠 Use Cases:

- `block`: Divisions, sections, paragraphs
- `inline`: Words, links, spans
- `inline-block`: Buttons, cards, icons
- `none`: Hide content with JavaScript or media queries


