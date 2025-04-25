## Purpose
- Defines structure and content for the homepage.
- Default entry point

## HTML notes
```
<!DOCTYPE html>
<!-- Declares the document type as HTML5 -->

<html lang="en">
<!-- Root element of your page. 'lang="en"' helps accessibility and SEO -->

<head>
  <meta charset="UTF-8" />
  <!-- Character encoding — standard for modern websites -->

  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <!-- Makes your site responsive on mobile devices -->

  <title>Page Title</title>
  <!-- Shows up in browser tab -->

  <link rel="stylesheet" href="style.css" />
  <!-- Links your external CSS file -->
</head>

<body>
  <!-- All visible content on the page goes here -->

  <h1>Main Heading</h1>       <!-- Big, bold top-level heading -->
  <h2>Subheading</h2>         <!-- Slightly smaller -->
  <p>This is a paragraph.</p> <!-- A block of text -->

  <a href="https://example.com" target="_blank">Visit Example</a>
  <!-- A link that opens in a new tab -->

  <img src="assets/images/photo.jpg" alt="Description" width="300" />
  <!-- An image with alt text and size -->

  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
  </ul>
  <!-- Unordered (bullet) list -->

  <ol>
    <li>First</li>
    <li>Second</li>
  </ol>
  <!-- Ordered (numbered) list -->

  <button>Click Me</button>
  <!-- Basic button — can be styled or connected to JS -->

  <div class="box">Container</div>
  <!-- A generic container, useful for layout and styling -->

  <section>
    <h2>About Me</h2>
    <p>This section contains info about me.</p>
  </section>
  <!-- Semantic section of content -->

  <script src="script.js"></script>
  <!-- Loads your JavaScript file -->
</body>
</html>
```