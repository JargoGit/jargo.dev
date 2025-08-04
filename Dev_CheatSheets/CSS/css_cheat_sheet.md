**CSS Cheat Sheet**

---

**CSS Syntax**

```css
selector {
  property: value;
}
```

---

**Selectors**

- Element: `p`, `h1`, `ul`, etc.
- Class: `.classname`
- ID: `#idname`
- Grouping: `h1, h2, h3 {}`
- Descendant: `.nav ul li {}`
- Child: `ul > li {}`
- Adjacent sibling: `h1 + p {}`
- Attribute: `input[type="text"] {}`
- Pseudo-class: `a:hover`, `:nth-child(2)`
- Pseudo-element: `p::first-line`

---

**Common Properties**

- Text:
  - `color`, `font-size`, `font-family`, `text-align`, `line-height`, `text-transform`, `text-decoration`
- Box Model:
  - `width`, `height`, `padding`, `margin`, `border`, `box-sizing`
- Display & Positioning:
  - `display: block | inline | inline-block | flex | grid | none`
  - `position: static | relative | absolute | fixed | sticky`
  - `top`, `right`, `bottom`, `left`, `z-index`
- Background:
  - `background-color`, `background-image`, `background-size`, `background-repeat`, `background-position`
- Border:
  - `border`, `border-radius`, `box-shadow`
- Flexbox:
  - `display: flex`, `justify-content`, `align-items`, `flex-direction`, `flex-wrap`, `gap`
- Grid:
  - `display: grid`, `grid-template-columns`, `grid-template-rows`, `gap`, `place-items`

---

**Units**

- Absolute: `px`, `pt`
- Relative: `%`, `em`, `rem`, `vw`, `vh`

---

**Responsive Design**

```css
@media (max-width: 768px) {
  body {
    font-size: 16px;
  }
}
```

---

**Colors**

- Named: `red`, `blue`
- Hex: `#ff0000`
- RGB: `rgb(255, 0, 0)`
- RGBA: `rgba(255, 0, 0, 0.5)`
- HSL: `hsl(0, 100%, 50%)`

---

**Typography Tips**

- Use `rem` for scalable font sizes
- Use `line-height: 1.5` for readability
- Use web-safe or Google Fonts

---

**Best Practices**

- Use class selectors for reusability
- Avoid `!important` unless necessary
- Organize with comments and group related styles
- Use shorthand when possible: `margin: 0 auto;`
- External stylesheets preferred over inline styles

---

**CSS Methodologies**

- BEM: `block__element--modifier`
- Utility-first: TailwindCSS approach

---

**Tools & References**

- [MDN CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [CSS Tricks](https://css-tricks.com/)
- [W3Schools CSS](https://www.w3schools.com/css/)
