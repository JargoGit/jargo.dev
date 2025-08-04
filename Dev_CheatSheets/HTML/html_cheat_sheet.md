**HTML Cheat Sheet**

---

**Basic Structure**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <!-- Content goes here -->
  </body>
</html>
```

---

**Common Tags**

- Headings: `<h1>` to `<h6>`
- Paragraph: `<p>`
- Link: `<a href="">Link</a>`
- Image: `<img src="" alt="" />`
- List (ul/ol):
  ```html
  <ul>
    <li>Item</li>
  </ul>
  <ol>
    <li>Item</li>
  </ol>
  ```
- Table:
  ```html
  <table>
    <tr><th>Head</th></tr>
    <tr><td>Data</td></tr>
  </table>
  ```
- Line Break: `<br />`
- Horizontal Rule: `<hr />`
- Strong/Bold: `<strong>` or `<b>`
- Emphasis/Italic: `<em>` or `<i>`

---

**Forms**

```html
<form action="/submit" method="post">
  <input type="text" name="name" />
  <input type="email" name="email" />
  <textarea name="message"></textarea>
  <button type="submit">Send</button>
</form>
```

**Form Input Types:**

- `text`
- `email`
- `password`
- `number`
- `submit`, `reset`, `button`
- `checkbox`, `radio`
- `file`
- `hidden`

---

**Semantic Elements**

- `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`
- `<aside>`, `<footer>`, `<figure>`, `<figcaption>`

**Section Tags, Classes, IDs & Best Practices**

- `<section>`: Groups related content; used inside `<main>` or `<article>`
- `class`: Used to apply CSS styles to multiple elements
  ```html
  <div class="card"></div>
  ```
- `id`: Unique identifier for a single element
  ```html
  <h1 id="intro"></h1>
  ```
- **Best Practices:**
  - Use `id` for JavaScript targeting or anchor links (1 per page)
  - Use `class` for styling and layout (reusable)
  - Use semantic tags (`<section>`, `<article>`, `<header>`, etc.) for clear structure and accessibility
  - Avoid too many nested `div`s (aka "div soup")

**Visual Layout Example:**

```html
<main>
  <header>
    <h1 class="site-title">My Portfolio</h1>
  </header>

  <nav class="main-nav">
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
    </ul>
  </nav>

  <section id="about" class="section">
    <h2>About Me</h2>
    <p>Short bio here...</p>
  </section>

  <section id="projects" class="section">
    <h2>My Projects</h2>
    <article class="project">
      <h3>Project One</h3>
      <p>Description...</p>
    </article>
  </section>

  <footer>
    <p>&copy; 2025 My Name</p>
  </footer>
</main>
```

---

**Media**

```html
<video controls>
  <source src="video.mp4" type="video/mp4" />
</video>
<audio controls>
  <source src="audio.mp3" type="audio/mp3" />
</audio>
```

---

**Meta Tags Examples**

```html
<meta name="description" content="Your description here" />
<meta name="keywords" content="HTML, CSS, Web" />
<meta name="author" content="Your Name" />
```

---

**Best Practices**

- Always include `alt` text for images
- Use semantic tags for accessibility & SEO
- Validate HTML with [validator.w3.org](https://validator.w3.org)

---

**Common Entities**

- `&nbsp;` (space)
- `&lt;` (<), `&gt;` (>)
- `&amp;` (&)
- `&quot;` (")
- `&copy;`, `&reg;`

---

**Comments**

```html
<!-- This is a comment -->
```

---

**Reference Sites**

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3Schools HTML](https://www.w3schools.com/html/)

