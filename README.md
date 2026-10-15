# 🌐 HTML Learning — Complete HTML5 Guide

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Web_Development-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/Learning-Hands--On-2EA44F?style=for-the-badge" alt="Hands-on Learning" />
  <img src="https://img.shields.io/badge/Level-Beginner_to_Intermediate-blue?style=for-the-badge" alt="Learning Level" />
  <img src="https://img.shields.io/badge/Focus-Semantic_HTML-orange?style=for-the-badge" alt="Semantic HTML" />
</p>

<p align="center">
  A practical learning repository for mastering HTML5, building structured web pages, working with multimedia, creating forms, and understanding modern web development fundamentals.
</p>

---

## 📌 About the Project

**HTML_learning** is a hands-on repository designed to help beginners understand **HyperText Markup Language (HTML)** through practical examples and demonstrations.

This repository explores the essential elements, attributes, and semantic structures used to build modern web pages. It also demonstrates how to embed images, audio, video, and PDF documents using HTML's built-in elements.

The project provides a foundation for learning CSS, JavaScript, responsive web design, and frontend development.

## 🎯 Learning Objectives

- Understand HTML document structure and syntax.
- Learn HTML elements, tags, and attributes.
- Create headings, paragraphs, lists, tables, and hyperlinks.
- Build forms using different input types.
- Structure pages with semantic HTML5 elements.
- Embed images, audio, video, and PDF documents.
- Explore SVG, Canvas, and interactive HTML elements.
- Improve accessibility and search engine optimization (SEO).
- Understand how HTML integrates with CSS and JavaScript.
- Follow clean and maintainable HTML coding practices.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure and content of web pages |
| SVG | Scalable vector graphics |
| HTML Forms | Collect user input |
| HTML Multimedia | Display images, audio, and video |
| JavaScript | Add behavior to web pages |
| Git & GitHub | Version control and project hosting |

## 📂 Repository Structure

```text
HTML_learning/
│
├── index.html     # Main HTML learning examples
├── Sample.png     # Sample image for HTML media demonstrations
├── Sample.mp3     # Sample audio file
├── Sample.mp4     # Sample video file
├── Sample.pdf     # Sample PDF document
└── README.md      # Project documentation
```

## 📚 Topics Covered

### 1. HTML Fundamentals

- Introduction to HTML and HTML5.
- HTML document structure.
- `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>`.
- Elements, tags, attributes, and nested elements.
- Comments and character entities.
- Metadata and page titles.

### 2. Text Formatting

- Headings: `<h1>` to `<h6>`.
- Paragraphs: `<p>`.
- Line breaks: `<br>`.
- Horizontal rules: `<hr>`.
- Bold and importance: `<b>` and `<strong>`.
- Italic and emphasis: `<i>` and `<em>`.
- Highlighted text: `<mark>`.
- Superscript and subscript: `<sup>` and `<sub>`.
- Preformatted text: `<pre>`.

### 3. Links and Navigation

- Anchor elements using `<a>`.
- Absolute and relative URLs.
- Internal page navigation.
- Email links using `mailto:`.
- Telephone links using `tel:`.
- Opening links in new tabs.
- Linking to sections using element IDs.

### 4. Lists

- Ordered lists: `<ol>`.
- Unordered lists: `<ul>`.
- List items: `<li>`.
- Description lists: `<dl>`, `<dt>`, and `<dd>`.
- Nested lists.

### 5. Tables

- Table structure using `<table>`.
- Table rows: `<tr>`.
- Header cells: `<th>`.
- Data cells: `<td>`.
- Table sections: `<thead>`, `<tbody>`, and `<tfoot>`.
- Merging cells with `rowspan` and `colspan`.
- Accessible table captions and headers.

### 6. Forms and Input Elements

- Form creation using `<form>`.
- Text, email, password, number, and date inputs.
- Radio buttons and checkboxes.
- File uploads.
- Dropdown lists using `<select>` and `<option>`.
- Multiline text using `<textarea>`.
- Submit and reset buttons.
- Labels, placeholders, required fields, and basic validation.

### 7. Semantic HTML5

- `<header>` — introductory content.
- `<nav>` — navigation links.
- `<main>` — primary page content.
- `<section>` — thematic grouping.
- `<article>` — self-contained content.
- `<aside>` — complementary content.
- `<footer>` — footer information.
- `<figure>` and `<figcaption>` — media with captions.

### 8. Images and Multimedia

- Images using `<img>`.
- Alternative text using `alt`.
- Audio playback using `<audio>`.
- Video playback using `<video>`.
- Media sources using `<source>`.
- PDF embedding using `<iframe>`, `<embed>`, and `<object>`.
- External content embedding.
- Multimedia fallback content.

### 9. Graphics and Interactive Elements

- SVG graphics using `<svg>`.
- Canvas basics using `<canvas>`.
- Expandable content using `<details>` and `<summary>`.
- Dialogs using `<dialog>`.
- Progress indicators using `<progress>`.
- Measurement indicators using `<meter>`.

### 10. JavaScript Integration

- Linking external JavaScript files using `<script>`.
- Inline and external script basics.
- Using `defer` and `async`.
- Fallback content with `<noscript>`.
- Understanding the relationship between HTML structure and JavaScript behavior.

### 11. Accessibility and SEO

- Using semantic elements appropriately.
- Writing meaningful page titles.
- Adding descriptive image alternative text.
- Associating labels with form inputs.
- Maintaining a logical heading hierarchy.
- Using descriptive link text.
- Specifying the document language.
- Including responsive viewport metadata.

### 12. Deprecated HTML Elements

Learn to recognize obsolete elements and understand why modern HTML alternatives should be preferred.

Examples include `<font>`, `<center>`, and `<marquee>`. Use CSS for presentation rather than obsolete styling elements.

## 💻 Example: Basic HTML5 Page

The following example demonstrates a clean HTML document structure.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Learn HTML5 through practical examples.">

    <title>HTML Learning</title>
</head>
<body>
    <header>
        <h1>Welcome to HTML Learning</h1>
        <p>Build your web development foundation.</p>
    </header>

    <main>
        <section>
            <h2>What is HTML?</h2>
            <p>
                HTML stands for HyperText Markup Language.
                It defines the structure and content of web pages.
            </p>
        </section>

        <section>
            <h2>Learning Resources</h2>
            <ul>
                <li>HTML fundamentals</li>
                <li>Forms and tables</li>
                <li>Semantic HTML</li>
            </ul>
        </section>

        <section>
            <h2>Explore More</h2>
            <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
                Learn HTML on MDN
            </a>
        </section>
    </main>

    <footer>
        <p>Keep learning and building!</p>
    </footer>
</body>
</html>
```

## 🎵 Multimedia Examples

The repository includes sample media files for practicing HTML multimedia elements.

### Display an Image

```html
<img src="Sample.png" alt="Sample image demonstration" width="400">
```

### Play Audio

```html
<audio controls>
    <source src="Sample.mp3" type="audio/mpeg">
    Your browser does not support audio playback.
</audio>
```

### Play Video

```html
<video controls width="640">
    <source src="Sample.mp4" type="video/mp4">
    Your browser does not support video playback.
</video>
```

### Embed a PDF

```html
<iframe
    src="Sample.pdf"
    width="100%"
    height="500"
    title="Sample PDF document">
</iframe>
```

**Note:** These examples assume the HTML file and sample media files are located in the same directory.

## 🚀 Practice Projects

Practice the concepts by building small projects as you progress.

| Level | Project | Concepts |
|---|---|---|
| 🟢 Beginner | Personal Profile Page | Headings, paragraphs, images |
| 🟢 Beginner | Favorite Websites Page | Links and lists |
| 🟢 Beginner | Student Timetable | Tables and captions |
| 🟡 Intermediate | Registration Form | Inputs, labels, validation |
| 🟡 Intermediate | Multimedia Gallery | Images, audio, video |
| 🟡 Intermediate | Resume Web Page | Semantic HTML and sections |
| 🔴 Advanced | Accessible Documentation Page | Navigation, landmarks, accessibility |
| 🔴 Advanced | Multi-Section Portfolio | Semantic structure and external assets |

## ⚙️ Getting Started

### Prerequisites

- A modern web browser such as Chrome, Firefox, or Edge.
- A code editor such as Visual Studio Code.
- Basic computer and file management skills.

### Step 1: Clone the Repository

```bash
git clone https://github.com/Saravanan-mc/HTML_learning.git
```

### Step 2: Navigate to the Project

```bash
cd HTML_learning
```

### Step 3: Open the Project

Open the folder in Visual Studio Code and edit `index.html`.

### Step 4: Run the HTML Page

Double-click `index.html` to open it in your browser, or use the Live Server extension in Visual Studio Code to preview changes while developing.

No build tools or package installation are required for the basic HTML examples.

## 📖 Recommended Learning Resources

- [MDN Web Docs — HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) — Comprehensive HTML documentation.
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/) — Beginner-friendly examples.
- [freeCodeCamp](https://www.freecodecamp.org/learn/) — Interactive web development lessons.
- [web.dev — Learn HTML](https://web.dev/learn/html/) — Modern HTML learning materials.
- [HTML Living Standard](https://html.spec.whatwg.org/) — Official HTML standard.

## 💡 Best Practices

- Use semantic HTML elements wherever appropriate.
- Keep HTML structure separate from CSS presentation.
- Always include the correct document type declaration.
- Specify the page language and character encoding.
- Add descriptive `alt` text to meaningful images.
- Associate form labels with their corresponding inputs.
- Use meaningful headings and descriptive links.
- Avoid deprecated HTML elements.
- Keep file names consistent and paths correct.
- Test pages in different browsers and screen sizes.
- Validate markup with the [W3C Markup Validation Service](https://validator.w3.org/).

## 🎓 Why Learn HTML?

HTML is the foundation of web development. It defines the structure and meaning of the content displayed in a browser.

Learning HTML helps you:

- Build structured web pages.
- Understand how websites work.
- Create accessible forms and content.
- Prepare for CSS and JavaScript.
- Develop frontend projects and personal portfolios.
- Build a foundation for frameworks such as React, Angular, and Vue.

## 👨‍💻 Author

**Saravanan-mc**

- GitHub Profile: [@Saravanan-mc](https://github.com/Saravanan-mc)
- Repository: [HTML_learning](https://github.com/Saravanan-mc/HTML_learning)

## ⭐ Support

If this repository helps you learn HTML, consider giving it a **star ⭐** on GitHub.

Keep practicing, explore new elements, and build your own web projects!

---

<p align="center">
  <b>Learn HTML • Structure the Web • Build Your Future 🚀</b>
</p>
