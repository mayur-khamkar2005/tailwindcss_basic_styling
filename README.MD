# 🚀 Tailwind CSS - Most Used Classes (Industry)

This file contains **commonly used Tailwind CSS classes (used in ~90% UI cases)** with their purpose and usage.

---

## 📦 1. Layout (Flexbox)

```html
flex
flex-col
flex-row
items-center
justify-center
justify-between
gap-2 gap-4 gap-6
```

**Use:** Navbar, card layout, alignment
**How:**

* `flex` → container ko flex banata hai
* `items-center` → vertical center
* `justify-between` → space between items

---

## 📏 2. Spacing

```html
p-2 p-4 p-6
px-4 py-2
m-2 m-4
mt-2 mb-4
```

**Use:** Space dene ke liye (UI clean banane ke liye)
**How:**

* `p` = padding (andar space)
* `m` = margin (bahar space)
* `px / py` = horizontal / vertical

---

## 📐 3. Width / Height

```html
w-full
w-1/2
w-80
h-full
h-screen
```

**Use:** Layout sizing control
**How:**

* `w-full` → full width
* `h-screen` → full screen height

---

## 🔤 4. Typography

```html
text-sm
text-lg
text-xl
font-semibold
font-bold
text-gray-500
text-white
```

**Use:** Text styling
**How:**

* `text-lg` → size bada
* `font-bold` → bold text
* `text-gray-500` → light color

---

## 🎨 5. Background & Colors

```html
bg-blue-500
bg-gray-100
bg-white
text-white
```

**Use:** Buttons, cards, sections
**How:**

* `bg-*` → background color
* `text-*` → text color

---

## 🔲 6. Border & Radius

```html
rounded
rounded-lg
rounded-xl
border
border-gray-200
```

**Use:** Modern UI (cards, buttons)
**How:**

* `rounded` → corners smooth
* `border` → border add

---

## 🌑 7. Shadow

```html
shadow
shadow-md
shadow-lg
```

**Use:** Cards, modals, dropdowns
**How:**

* Depth effect deta hai UI ko

---

## ⚡ 8. Hover & Transition

```html
hover:bg-blue-600
hover:scale-105
transition
duration-300
```

**Use:** Interaction (buttons, cards)
**How:**

* `hover:*` → hover pe change
* `transition` → smooth effect

---

## 📍 9. Position

```html
relative
absolute
top-0
left-0
```

**Use:** Badge, overlay, dropdown
**How:**

* `relative` → parent
* `absolute` → child positioning

---

## 🔳 10. Grid

```html
grid
grid-cols-2
grid-cols-3
gap-4
```

**Use:** Product listing, dashboard
**How:**

* `grid-cols-3` → 3 columns

---

## 💡 Example

```jsx
<div className="w-80 p-4 bg-white rounded-xl shadow-md flex flex-col gap-2">
  <h2 className="text-lg font-bold">Product</h2>
  <p className="text-gray-500">Description</p>
  <button className="px-4 py-2 bg-blue-500 text-white rounded hover:bg-blue-600 transition">
    Buy
  </button>
</div>
```

---
