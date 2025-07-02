# 📌 Sticky Header Webpage

This project shows how to build a **sticky header** using **HTML** and **CSS**.

---

## ✅ Features

- **Sticky header** stays fixed at the top while scrolling.
- Includes a **logo** and a **horizontal navigation menu**.
- Uses **flexbox** for clean layout and spacing.
- Adds padding and a subtle shadow for a modern look.
- Page content does not hide behind the header.

---

## 📂 Files

- `index.html` – The main HTML file.
- `styles.css` – The stylesheet with header styling.

---

## 💡 How it works

- `position: fixed` keeps the header stuck to the top.
- `box-shadow` adds depth.
- Flexbox arranges logo and nav links.
- The `<main>` uses `margin-top` to prevent overlap.

---

## 🚀 How to use

1. Clone or download this repository.
2. Open `index.html` in your web browser.
3. Scroll the page — the header stays fixed!

---

## ✨ Example

```html
<header class="sticky-header">
  <div class="logo">MyLogo</div>
  <nav class="nav">
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
  </nav>
</header>
