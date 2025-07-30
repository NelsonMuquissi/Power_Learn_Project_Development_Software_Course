# 🎨 Understanding the CSS Box Model – Week 3 Assignment

**Student:** Nelson Muquissi  
**Cohort:** PLP – Web Technologies (July 2025)  
**Repository:** `july-2025-introduction-to-css-NelsonMuquissi`

---

## 📘 Assignment Overview

This week's assignment was focused on **CSS fundamentals**, especially the **Box Model**, which defines how HTML elements are visually structured and spaced on the page. We explored how `margin`, `border`, `padding`, and `content` work together to build responsive, organized layouts.

No JavaScript was required. The focus was on practicing **pure CSS and semantic HTML** to create structured and visually clear boxes using the box model and layout principles.

---

## 🎯 Objectives

- Understand and apply the **CSS Box Model** components:
  - `content`, `padding`, `border`, `margin`
- Use the `box-sizing` property and observe the difference between:
  - `content-box` (default)
  - `border-box` (recommended)
- Design **three visual cards** with proper spacing and borders
- Implement layout using **flexbox**
- Reinforce **semantic HTML structure** and clean code practices

---

## 📁 Deliverables

The main deliverable is the file: `index.html`, which includes:

- ✅ Three styled boxes (`.card`) using Box Model  
- ✅ Responsive layout using `flex-wrap` and `gap`  
- ✅ Borders, internal spacing (`padding`), and external spacing (`margin`)  
- ✅ Toggle between `box-sizing: content-box` and `border-box` for comparison  
- ✅ Semantic HTML structure: `<header>`, `<main>`, `<section>`  

---

## 📚 What I Learned

- The **Box Model** is essential to every element’s layout:  
  - `margin` → space *outside* the element  
  - `border` → line surrounding the element  
  - `padding` → space *inside* the element, between content and border  
  - `content` → actual text/image/content inside the box

- The `box-sizing` property affects **how total width/height is calculated**:
  - With `content-box`, padding and border add to the width
  - With `border-box`, padding and border are *inside* the declared width

- How to use **flexbox** to arrange multiple cards responsively

- The importance of **semantic HTML tags** even when the focus is on CSS

---

## 💡 Example Snippet

```css
.card {
  padding: 20px;
  margin: 10px;
  border: 2px solid #333;
  box-sizing: border-box;
}

<div class="card">
  <h2>Card Title</h2>
  <p>This is a sample card using the CSS box model.</p>
</div>
