HTML Theoretical Questions

Q1. What is HTML and what is the difference between HTML and HTML5?

HTML (HyperText Markup Language) is the standard language used to create web pages. It structures content such as headings, paragraphs, images, links, and forms.

HTML5 is the latest version of HTML. It introduced new semantic tags, multimedia support, and improved APIs for modern web development.

Example

<video controls>
  <source src="movie.mp4" type="video/mp4">
</video>

---

Q2. What are semantic HTML tags? Why are they important?

Semantic tags clearly describe the meaning of the content inside them.

Examples

- "<header>"
- "<footer>"
- "<article>"
- "<section>"
- "<nav>"

Importance

- Improve readability of code
- Help search engines understand content
- Improve accessibility for screen readers
- Make website structure organized

Example

<header>
  <h1>My Website</h1>
</header>

---

Q3. What is the difference between "<div>" and "<span>" tags?

Tag| Type| Usage
"<div>"| Block-level element| Takes full width and used for large sections
"<span>"| Inline element| Takes only needed width and used for small text styling

Example

<div>
  <p>This is inside div</p>
</div>

<span style="color:red;">Red Text</span>

---

Q4. Explain the difference between block-level and inline elements.

Block-level Elements

- Start on a new line
- Take full width available

Examples:
"<div>", "<p>", "<h1>"

Inline Elements

- Do not start on a new line
- Take only necessary width

Examples:
"<span>", "<a>", "<strong>"

---

Q5. What is the purpose of the DOCTYPE declaration in HTML?

The "<!DOCTYPE html>" declaration tells the browser that the document uses HTML5. It helps browsers render pages correctly.

Example

<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
</head>
<body>
</body>
</html>

---

Q6. What is the difference between "id" and "class" attributes?

Attribute| Description
"id"| Unique for one element and accessed with "#" in CSS
"class"| Can be used on multiple elements and accessed with "." in CSS

Example

<p id="title">Hello</p>

<p class="text">Paragraph 1</p>
<p class="text">Paragraph 2</p>

---

Q7. How do you create a form in HTML? Which input types are commonly used?

Forms are created using the "<form>" tag to collect user data.

Common Input Types

- "text"
- "email"
- "password"
- "checkbox"
- "submit"

Example

<form>
  <input type="text" placeholder="Enter name">
  <input type="email" placeholder="Enter email">
  <input type="password" placeholder="Password">
  <input type="submit">
</form>

---

Q8. What are meta tags in HTML and why are they used?

Meta tags provide information about a webpage to browsers and search engines.

Uses

- Define character encoding
- Improve SEO
- Control page responsiveness

Example

<meta charset="UTF-8">
<meta name="description" content="HTML Tutorial">

---

Q9. Explain the purpose of the "alt" attribute in the "<img>" tag.

The "alt" attribute provides alternative text for images.

Importance

- Helps visually impaired users using screen readers
- Displays text if image fails to load
- Improves SEO

Example

<img src="cat.jpg" alt="White cat sitting on sofa">

---

Q10. How do you make an image clickable in HTML?

You can make an image clickable by placing it inside an "<a>" tag.

Example

<a href="https://example.com">
  <img src="image.jpg" alt="Sample Image">
</a>

---

Q11. What is the difference between JPG, PNG, SVG, and WebP image formats?

Format| Best Use
JPG| Photos and compressed images
PNG| Transparent images
SVG| Vector graphics and logos
WebP| Modern format with better compression

---

Q12. What are semantic tags introduced in HTML5 such as "<header>", "<footer>", "<section>", and "<article>"?

These tags describe webpage structure clearly.

- "<header>" → Top section of page
- "<footer>" → Bottom section
- "<section>" → Groups related content
- "<article>" → Independent content block

Example

<article>
  <h2>Blog Title</h2>
  <p>Blog content...</p>
</article>

---

Q13. What is the difference between "<script>", "async", and "defer" in HTML?

"<script>"

Loads and executes immediately.

"async"

Downloads script in parallel and executes immediately after download.

"defer"

Downloads in parallel but executes after HTML parsing is complete.

Example

<script src="app.js" defer></script>

---

Q14. How do you embed audio and video in HTML5?

HTML5 uses "<audio>" and "<video>" tags.

Example

<audio controls>
  <source src="music.mp3" type="audio/mpeg">
</audio>

<video controls width="400">
  <source src="movie.mp4" type="video/mp4">
</video>

---

Q15. What is the difference between relative paths and absolute paths in HTML?

Relative Path

Points to a file relative to the current folder.

<img src="images/photo.jpg">

Absolute Path

Contains the full URL.

<img src="https://example.com/photo.jpg">

---

Q16. What are data attributes in HTML ("data-*")? Where are they used?

Data attributes store custom information inside HTML elements.

Example

<button data-id="101">Click</button>

---

Q17. What is the purpose of the viewport meta tag in responsive web design?

The viewport meta tag controls how a webpage appears on mobile devices.

Example

<meta name="viewport" content="width=device-width, initial-scale=1.0">

This helps websites adjust properly on different screen sizes.

---

Q18. How can you improve SEO using HTML?

Ways to Improve SEO

- Use semantic tags
- Add proper headings ("<h1>" to "<h6>")
- Use meaningful meta descriptions
- Add alt text to images
- Use clean URLs and readable content

Example

<meta name="description" content="Learn HTML basics">

---

Q19. What are accessibility best practices in HTML?

Accessibility makes websites usable for everyone.

Best Practices

- Use semantic HTML
- Add alt text to images
- Use labels for forms
- Ensure keyboard navigation
- Maintain proper color contrast

Example

<label for="email">Email</label>
<input type="email" id="email">

---

Q20. What is the difference between "<strong>" vs "<b>" and "<em>" vs "<i>" tags?

Tag| Meaning
"<strong>"| Important text
"<b>"| Bold text only
"<em>"| Emphasized text
"<i>"| Italic text only

Example

<strong>Important</strong>
<b>Bold</b>

<em>Emphasized</em>
<i>Italic</i>
