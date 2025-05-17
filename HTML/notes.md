# Introduction to HTML

by tim berner lee

This section provides an overview of HTML and its role in web development.

**Hypertext Markup Language (HTML)**  
- The backbone of web pages, as old as the internet itself.

---

# What is HTML?

HTML (Hypertext Markup Language) is the standard language for creating web pages.  
- **index.html**: The instruction manual for a website, guiding the browser to load JavaScript, CSS, images, and other resources.  
- Every website is essentially a folder on a computer, assembled by the browser using HTML instructions.  
- HTML can include plain content but is primarily structured using **HTML elements**.

---

# HTML Elements

HTML elements are building blocks of a web page, defined by tags.  
- **Common Tags**: `<h1>`, `<h2>`, `<h3>`, etc., for headings.  
- **Structure**:  
  - All content is placed within the `<html>` tag.  
  - `<head>`: Contains metadata, scripts, and links (e.g., CSS files).  
  - `<body>`: Holds the main visible content of the website.  
- **Boilerplate**: Use `!` in editors to generate a standard HTML template.  

**Common Elements**:  
1. `<p>`: Paragraph text.  
2. `<u>`, `<strong>`: Underline and bold text, respectively.  
3. **Nested Elements**: Elements can be placed inside other elements for complex structures.

---

# HTML Attributes

Attributes provide additional information about HTML elements.  
- **Global Attributes**: `class`, `id` (used across many elements).  
- **Specific Attributes**:  
  - `<img>`: Uses `src` (image source), `alt` (alternative text), `width`, `height`.  
  - `<a>` (anchor): Uses `href` (link URL).  
- **Lists**:  
  - Ordered (`<ol>`) and unordered (`<ul>`) lists use `<li>` for each list item.  
- **Buttons**: Used for links or actions.  
- **Forms**:  
  - `<form>`: Contains inputs for user data (e.g., login, payment).  
  - `<input>`: Uses `type` (e.g., text, password) and `id`.  
  - `<label>`: Links to an input via the `for` attribute, matching the input’s `id`.  
  - Other attributes: `disabled`, etc. (refer to documentation for details).

---

# Container Elements

Container elements group and organize content.  
- **Common Containers**:  
  - `<div>`: Generic block container.  
  - `<span>`: Generic inline container.  
- **Anti-Div Movement**: Advocates for semantic containers over generic `<div>`s.

---

# Script and Style Tags

- `<script>`: Embeds or links to JavaScript code.  
- `<style>`: Embeds CSS for styling.  
- These tags allow HTML, CSS, and JavaScript to coexist in a single HTML file.

---

# Anti-Div Movement

Encourages the use of **semantic HTML** for better structure and accessibility.  
- Examples of semantic elements:  
  - `<header>`: Page or section header.  
  - `<nav>`: Navigation links.  
  - `<article>`: Independent content.  
  - `<figure>`: Images or illustrations with captions.  
  - `<footer>`: Page or section footer.  

Semantic elements describe their purpose clearly, improving readability and SEO.