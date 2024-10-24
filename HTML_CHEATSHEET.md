# HTML Tags Cheat Sheet

## Basic Tags

| Tag        | Description                                              | Example                                |
|------------|----------------------------------------------------------|----------------------------------------|
| `<!DOCTYPE>` | Declares the document type (HTML5)                        | `<!DOCTYPE html>`                     |
| `<html>`     | Root element of an HTML document                          | `<html></html>`                       |
| `<head>`     | Contains metadata and links to external resources         | `<head></head>`                       |
| `<title>`    | Sets the title of the webpage (appears in browser tab)    | `<title>My Page</title>`              |
| `<meta>`     | Defines metadata (e.g., charset, viewport)                | `<meta charset="UTF-8">`              |
| `<link>`     | Links to external resources (e.g., stylesheets)           | `<link rel="stylesheet" href="styles.css">` |
| `<script>`   | Embeds or links to JavaScript code                        | `<script src="app.js"></script>`      |
| `<style>`    | Embeds internal CSS styles                                | `<style>body { color: red; }</style>` |

## Text Formatting

| Tag        | Description                                              | Example                                |
|------------|----------------------------------------------------------|----------------------------------------|
| `<h1> - <h6>` | Headings (h1 is the largest, h6 is the smallest)         | `<h1>Main Heading</h1>`               |
| `<p>`        | Paragraph of text                                        | `<p>This is a paragraph.</p>`         |
| `<br>`       | Inserts a line break                                     | `Line 1<br>Line 2`                    |
| `<hr>`       | Inserts a horizontal rule/line                           | `<hr>`                                |
| `<strong>`   | Makes text bold (semantically important)                 | `<strong>Important</strong>`          |
| `<em>`       | Italicizes text (semantically emphasized)                | `<em>Emphasized text</em>`            |
| `<b>`        | Makes text bold (non-semantic)                           | `<b>Bold text</b>`                    |
| `<i>`        | Italicizes text (non-semantic)                           | `<i>Italic text</i>`                  |
| `<u>`        | Underlines text                                          | `<u>Underlined text</u>`              |
| `<small>`    | Displays smaller-sized text                              | `<small>Small text</small>`           |
| `<mark>`     | Highlights text                                          | `<mark>Highlighted text</mark>`       |

## Links and Images

| Tag        | Description                                              | Example                                |
|------------|----------------------------------------------------------|----------------------------------------|
| `<a>`        | Creates a hyperlink                                      | `<a href="https://example.com">Visit</a>` |
| `<img>`      | Embeds an image                                          | `<img src="image.jpg" alt="Description">` |

## Lists

| Tag        | Description                                              | Example                                |
|------------|----------------------------------------------------------|----------------------------------------|
| `<ul>`       | Unordered (bulleted) list                                | `<ul><li>Item 1</li><li>Item 2</li></ul>` |
| `<ol>`       | Ordered (numbered) list                                  | `<ol><li>Item 1</li><li>Item 2</li></ol>` |
| `<li>`       | List item in an ordered or unordered list                | `<li>Item</li>`                       |

## Tables

| Tag        | Description                                              | Example                                |
|------------|----------------------------------------------------------|----------------------------------------|
| `<table>`    | Defines a table                                           | `<table></table>`                     |
| `<tr>`       | Table row                                                 | `<tr><td>Data</td></tr>`              |
| `<td>`       | Table data/cell                                           | `<td>Cell data</td>`                  |
| `<th>`       | Table header cell                                         | `<th>Header</th>`                     |
| `<thead>`    | Groups header rows in a table                             | `<thead><tr><th>Header</th></tr></thead>` |
| `<tbody>`    | Groups the body content in a table                        | `<tbody><tr><td>Data</td></tr></tbody>` |
| `<tfoot>`    | Groups footer rows in a table                             | `<tfoot><tr><td>Footer</td></tr></tfoot>` |

## Forms

| Tag        | Description                                              | Example                                |
|------------|----------------------------------------------------------|----------------------------------------|
| `<form>`     | Defines a form for user input                             | `<form action="/submit"></form>`       |
| `<input>`    | Input field (text, password, email, etc.)                 | `<input type="text">`                  |
| `<button>`   | Clickable button                                          | `<button>Submit</button>`              |
| `<label>`    | Label for form elements                                   | `<label for="name">Name</label>`       |
| `<select>`   | Dropdown list                                             | `<select><option>Option</option></select>` |
| `<option>`   | Option inside a dropdown                                  | `<option>Choice 1</option>`            |
| `<textarea>` | Multi-line text input area                                | `<textarea>Enter text</textarea>`      |
| `<fieldset>` | Groups related elements in a form                         | `<fieldset><legend>Info</legend></fieldset>` |

## Semantic Elements

| Tag        | Description                                              | Example                                |
|------------|----------------------------------------------------------|----------------------------------------|
| `<header>`   | Defines a header section                                  | `<header>Site Header</header>`         |
| `<footer>`   | Defines a footer section                                  | `<footer>Site Footer</footer>`         |
| `<nav>`      | Navigation links section                                  | `<nav><a href="#">Link</a></nav>`      |
| `<article>`  | Independent, self-contained content                       | `<article>Blog post content</article>` |
| `<section>`  | Defines a section of content                              | `<section>Page section</section>`      |
| `<aside>`    | Content related to the main content (like a sidebar)      | `<aside>Related links</aside>`         |
| `<main>`     | Main content of the document                              | `<main>Main content here</main>`       |

## Media

| Tag        | Description                                              | Example                                |
|------------|----------------------------------------------------------|----------------------------------------|
| `<audio>`    | Embeds audio content                                      | `<audio controls><source src="audio.mp3" type="audio/mpeg"></audio>` |
| `<video>`    | Embeds video content                                      | `<video controls><source src="video.mp4" type="video/mp4"></video>`  |
| `<source>`   | Specifies media resources for audio or video              | `<source src="media.mp4" type="video/mp4">`                          |

## Other Tags

| Tag        | Description                                              | Example                                |
|------------|----------------------------------------------------------|----------------------------------------|
| `<div>`      | Generic block-level container                            | `<div>Block element</div>`             |
| `<span>`     | Generic inline container                                 | `<span>Inline element</span>`          |
| `<iframe>`   | Embeds another HTML page                                 | `<iframe src="page.html"></iframe>`    |
| `<noscript>` | Fallback content for users with JavaScript disabled       | `<noscript>Your browser does not support JavaScript.</noscript>` |