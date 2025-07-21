
# 🎨 Style Guide

Bu `style-guide.md` Huddle landing page with single introductory section loyihasi uchun asosiy ranglar, shriftlar va umumiy qo‘llanmalarni o‘z ichiga oladi.

---

## 📌 Colors / Ranglar

### 🎨 Primary Colors

- **Purple:** `hsl(257, 40%, 49%)`
- **Magenta (Accent):** `hsl(300, 69%, 71%)`
- **White:** `#ffffff`

---

## 📌 Typography / Shrifts

- **Font Family:** `'Poppins', sans-serif`

### 📏 Font Weights

- 400 - Normal
- 500 - Medium
- 600 - Semi-Bold
- 700 - Bold

---

## 📌 Layout

- **Max Container Width:** `1300px`
- **Padding:** `0 20px` (asosiy konteynerlar uchun)

---

## 📌 Images

- **Background Desktop:** `bg-desktop.svg`
- **Background Mobile:** `bg-mobile.svg`
- **Logo:** `logo.svg`
- **Hero Image:** `illustration-mockups.svg`

---

## 📌 Buttons

- **Button Border Radius:** `50px`
- **Button States:**
  - Hover: Orqa fon `Magenta`, matn rangi `White`
  - Focus: `outline` bilan ajratiladi (`outline: 2px solid hsl(300, 69%, 71%)`)

---

## 📌 Social Icons

- **Ikon font:** Font Awesome (`6.4.0`)
- **Ikon hover:** Oq fon + Purple rang ikon uchun (`hsl(257, 40%, 49%)`)

---

## 📌 Breakpoints / Responsivlik

- **Desktop:** > 768px
- **Mobile:** ≤ 768px

---

## 📌 Accessibility / Kirish imkoniyati

- **Screen Reader Text:** `.sr-only` klassi bilan yashirin matn
- **Focus states:** Klaviatura navigatsiyasi uchun aniq `outline`

```css
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}
```

---

## 📌 Ikonlar

- **Facebook:** `<i class="fa-brands fa-facebook-f"></i>`
- **Twitter:** `<i class="fa-brands fa-twitter"></i>`
- **Instagram:** `<i class="fa-brands fa-instagram"></i>`

---

## 📌 Fonts CDN

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
```

---

## 📌 Ikonlar CDN

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

---

✅ Shu style-guide sizga loyihani tartibli va yagona uslubda ishlab chiqishda yordam beradi.

---

