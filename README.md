**CSS Basics: Notes from Sessions 2 & 3**

---

### Session 2: Styling Text and Colors

**What is CSS?**
- CSS stands for Cascading Style Sheets.
- It controls how HTML content looks (colors, fonts, spacing, etc).
- CSS is separate from HTML structure but works together with it.

**Three Ways to Add CSS:**
1. **Inline:** Directly in an HTML tag using `style=""` (not recommended for full projects).
2. **Internal:** In a `<style>` tag inside the `<head>` of your HTML file.
3. **External:** In a `.css` file linked using `<link rel="stylesheet" href="style.css">`.

**CSS Syntax:**
```css
selector {
  property: value;
}
```
Example:
```css
h1 {
  color: red;
  font-size: 32px;
}
```

**Text Styling Properties:**
- `color`: changes the text color.
- `font-family`: sets the font (e.g. Arial, Georgia).
- `font-size`: controls the size of the text.
- `font-style`: normal / italic / oblique.
- `font-weight`: normal / bold / 100–900.

**Color Formats:**
- **Named Colors**: red, blue, green, etc.
- **Hex Codes**: `#ff0000` (red), `#000000` (black), `#ffffff` (white).
- **RGB**: `rgb(255, 0, 0)`
- **RGBA**: `rgba(0, 0, 255, 0.5)` (adds transparency)

**Tips:**
- Use `class="name"` in HTML to target specific elements in CSS.
- Use `background-color` to highlight areas and practice layout.

---

### Session 3: The Box Model & Layout Basics

**The Box Model:**
Every element on a webpage is a rectangular box made of:
1. **Content** – the text or image inside the element
2. **Padding** – space *inside* the box, around the content
3. **Border** – the edge of the box
4. **Margin** – space *outside* the box, between this element and others

**CSS Example:**
```css
.card {
  padding: 20px;
  margin: 15px;
  border: 2px solid navy;
  background-color: lightblue;
  width: 300px;
}
```

**Display Types:**
- `block`: takes full width, always starts on a new line (e.g. `<div>`, `<p>`)
- `inline`: only takes up as much width as its content (e.g. `<span>`, `<a>`)
- `inline-block`: like inline, but you can set width and height
- `none`: hides the element completely

**Spacing Properties:**
- `padding`: space between content and border
- `margin`: space outside the border, separating elements
- You can set individual sides like:
  - `padding-top`, `margin-left`, etc.

**Visual Debugging Tip:**
Use different `background-color`s and borders to see how boxes are arranged on the page.

**Helpful Units:**
- `px`: fixed size in pixels
- `%`: relative to the parent
- `em` and `rem`: relative to font size (advanced, but useful later)

**Best Practice:**
Use the **Inspect Tool** (right-click > Inspect) in your browser to view and experiment with styles.

---

**Coming Up in Week 6:**
- Flexbox and Grid: more advanced ways to lay out and align elements easily!
- You’ll learn how to center stuff (finally!).
