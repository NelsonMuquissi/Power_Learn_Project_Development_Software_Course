# 🌐 Mastering the DOM with JavaScript

DOM manipulation lets you interact with HTML dynamically.

## Topics Covered
- Selecting elements (`getElementById`, `querySelector`)
- Modifying content and styles
- Adding/removing classes
- Handling events (`click`, `input`, etc.)
- Creating elements dynamically

## Example
```javascript
document.getElementById("btn").addEventListener("click", () => {
  document.body.style.backgroundColor = "lightblue";
});