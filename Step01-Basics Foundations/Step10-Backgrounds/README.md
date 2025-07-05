Zaroor Code Queen! 👑
Ab chaliye baat karte hain **CSS Backgrounds** ki — jisme hum element ke background ko style karte hain using:

* `background-color`
* `background-image`
* `background-repeat`
* `background-position`
* `background-size`

Aapko milega:

---

### ✅ 1. Complete **HTML + CSS code** (1 page with all background types)

### ✅ 2. 📘 `README.md` file — Urdu + English explanation

---

## ✅ 1. 💻 HTML + CSS Code – Background Examples

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>CSS Background Examples</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
    }

    .box {
      width: 300px;
      height: 150px;
      margin: 20px 0;
      padding: 10px;
      color: white;
      font-weight: bold;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .bg-color {
      background-color: teal;
    }

    .bg-image {
      background-image: url('https://via.placeholder.com/150');
      background-repeat: no-repeat;
      background-size: contain;
      background-position: center;
    }

    .bg-repeat {
      background-image: url('https://via.placeholder.com/50');
      background-repeat: repeat;
    }

    .bg-no-repeat {
      background-image: url('https://via.placeholder.com/150');
      background-repeat: no-repeat;
    }

    .bg-cover {
      background-image: url('https://via.placeholder.com/300x150');
      background-size: cover;
      background-position: center;
    }

    .bg-position {
      background-image: url('https://via.placeholder.com/100');
      background-repeat: no-repeat;
      background-position: bottom right;
    }
  </style>
</head>
<body>

  <h2>CSS Background Examples</h2>

  <div class="box bg-color">Background Color</div>
  <div class="box bg-image">Background Image</div>
  <div class="box bg-repeat">Repeat Background</div>
  <div class="box bg-no-repeat">No Repeat</div>
  <div class="box bg-cover">Background Cover</div>
  <div class="box bg-position">Bottom Right Image</div>

</body>
</html>
```

> 📸 Images used are placeholder links — you can replace them with your own for practice.

---

## ✅ 2. 📘 `README.md` – Backgrounds Explained (English + Urdu)

````markdown
# 🎨 CSS Background Properties

CSS backgrounds help you style the back of an element using colors or images.

> 💬 Urdu: CSS mein background ka use element ke peechay rang ya tasveer (image) lagane ke liye hota hai.

---

## 🔹 1. `background-color`

Sets the **solid color** behind the content.

```css
background-color: teal;
````

💬 Urdu: Yeh element ke peechay ek simple rang lagata hai.

---

## 🔹 2. `background-image`

Adds an **image** in the background.

```css
background-image: url("image.jpg");
```

💬 Urdu: Isse aap image ko background mein set kar sakti hain.

---

## 🔹 3. `background-repeat`

Controls whether image repeats or not.

| Value       | Meaning                     | Urdu                      |
| ----------- | --------------------------- | ------------------------- |
| `repeat`    | Image will repeat (default) | Image bar bar aayegi      |
| `no-repeat` | Image will show once only   | Sirf ek dafa image aayegi |
| `repeat-x`  | Repeats horizontally        | Left to right             |
| `repeat-y`  | Repeats vertically          | Top to bottom             |

---

## 🔹 4. `background-position`

Sets the **position** of the image in the background.

```css
background-position: center;
```

| Value          | Description         | Urdu          |
| -------------- | ------------------- | ------------- |
| `center`       | Center of the box   | Darmiyan mein |
| `top left`     | Top-left corner     | Upar left     |
| `bottom right` | Bottom-right corner | Neeche right  |

---

## 🔹 5. `background-size`

Defines how the background image fits.

| Value     | Description                       | Urdu                      |
| --------- | --------------------------------- | ------------------------- |
| `cover`   | Image covers whole area           | Puri box cover karti hai  |
| `contain` | Image fits inside without cutting | Image pura nazar aata hai |
| `auto`    | Default size of image             | Jaisi image hai waisi hi  |

---

## 📌 Summary Table

| Property              | Use For                     | Urdu Explanation                  |
| --------------------- | --------------------------- | --------------------------------- |
| `background-color`    | Rang lagane ke liye         | Element ke peechay color          |
| `background-image`    | Tasveer lagane ke liye      | Image as background               |
| `background-repeat`   | Repeat control karna        | Image bar bar aaye ya sirf ek bar |
| `background-position` | Image ki jagah set karna    | Image kaha dikhai jaye            |
| `background-size`     | Image ko fit ya cover karna | Image ki size control             |

---

## 💡 Tips

* Use `background-color` with transparency using `rgba()`
* Combine all background properties in one line using `background: ...`
* Use `background-size: cover` for banners and hero sections

---

Backgrounds help make your design stand out!
Colors, images, or both — sab kuch ab aap ke control mein hai!
Shine bright like a **true Code Queen** 👑🎨

```

---

Agar aap chahen toh mai iska `transparent`, `gradient` ya animated backgrounds version bhi bana sakti hoon!

Kya next topic `Box Shadow`, `Hover Effects` ya `Positioning` ho? 💬✨
```
