# 0x00. Advanced HTML

Welcome to the Advanced HTML readme!

## Guidelines for HTML

When writing HTML code, it's essential to follow best practices and guidelines to ensure consistency, accessibility, and maintainability. Some key guidelines include:

- **Use proper indentation**: Indentation helps improve readability and maintainability of the code.
- **Use lowercase tags**: HTML tags should be written in lowercase for consistency.
- **Provide meaningful and descriptive names for elements**: Use semantic names that accurately describe the content or purpose of the elements.
- **Use valid HTML syntax**: Ensure your HTML code adheres to the HTML specification to avoid rendering issues and compatibility problems across browsers.
- **Optimize for accessibility**: Make your HTML accessible to all users, including those with disabilities, by using semantic markup, providing alternative text for images, and ensuring keyboard navigation.

## Creating the Skeleton of an HTML5 Page

To create the skeleton of an HTML5 page, you can use the following structure:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <!-- Your content goes here -->
  </body>
</html>
```

This structure includes the `<!DOCTYPE html>` declaration, the `<html>`, `<head>`, and `<body>` elements, and basic meta tags.

## Using Semantic HTML Tags to Structure a Web Page

Semantic HTML tags provide meaning to the content they contain and help search engines and screen readers understand the structure of a web page. Some common semantic tags include:

- `<header>`: Represents introductory content or a group of navigational links.
- `<main>`: Contains the main content of the web page.
- `<footer>`: Represents the footer of a document or section.
- `<article>`: Represents a self-contained piece of content, such as a blog post or article.
- `<nav>`: Contains navigation links.
- `<section>`: Represents a thematic grouping of content.
- `<aside>`: Represents content aside from the main content, like sidebars or pull quotes.

Using semantic HTML tags improves accessibility and SEO while providing a clear structure to your web page.

## Use Cases for div vs span

- `<div>`: Used for grouping block-level elements or sections of content. It's suitable for styling with CSS and creating layout structures.
- `<span>`: Used for styling inline elements or applying styles to a specific part of text within a block-level element.

## Semantic Values of Semantic Tags

- **header**: Introduces the content at the beginning of a section or page.
- **main**: Contains the primary content of the document.
- **footer**: Represents the footer of a document or section.
- **article**: Represents a self-contained piece of content that can be independently distributed or reused.
- **nav**: Contains navigation links.
- **section**: Represents a thematic grouping of content.
- **aside**: Represents content that is tangentially related to the content around it.

## Using Headings

Headings (`<h1>` to `<h6>`) are important for structuring content and providing hierarchy. Follow the hierarchical order to maintain semantic meaning and improve accessibility. For example, `<h1>` is the main heading, followed by `<h2>` for subheadings, and so on.

## Making Lists in HTML

HTML provides different types of lists:

- **Ordered list (`<ol>`)**: Represents a list of items in a specific order, typically rendered with numbers.
- **Unordered list (`<ul>`)**: Represents a list of items in no particular order, typically rendered with bullets.
- **Definition list (`<dl>`)**: Represents a list of term-definition pairs.

Use the appropriate list type based on the content you want to present.

## Differences Between Media Types

- **SVG (Scalable Vector Graphics)**: Vector-based format suitable for graphics, icons, and illustrations. Scalable without loss of quality.
- **GIF (Graphics Interchange Format)**: Bitmap image format supporting animation and transparency but with limited colors.
- **PNG (Portable Network Graphics)**: Bitmap image format supporting lossless compression and transparency. Suitable for graphics and images.
- **JPG/JPEG (Joint Photographic Experts Group)**: Lossy compression format suitable for photographs and complex images.

## Structuring Data in a Table

Use the `<table>`, `<tr>`, `<th>`, and `<td>` elements to create tables in HTML. `<th>` represents table headers, `<tr>` represents table rows, and `<td>` represents table data cells.

## Integrating Video and Audio in a Web Page

To integrate video, use the `<video>` element and specify the video source using the `<source>` element. For audio, use the `<audio>` element with `<source>` elements for different audio formats.

Example for video:

```html
<video controls>
  <source src="movie.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video>
```

Example for audio:

```html
<audio controls>
  <source src="audio.mp3" type="audio/mp3" />
  Your browser does not support the audio tag.
</audio>
```

## Embedding External Content

To embed external content, you can use `<iframe>` for embedding web pages or `<embed>` for embedding multimedia content like videos, audio, or interactive applications.

Example for embedding a webpage:

```html
<iframe src="https://example.com"></iframe>
```

## Correctly Structuring an HTML Page

A correctly structured HTML page follows the HTML5 standard, includes appropriate meta tags, uses semantic HTML elements for content, and adheres to accessibility guidelines.

## Resources

- [HTML Living Standard](https://html.spec.whatwg.org/multipage/)
- [HTML Reference](https://htmlreference.io/)
- [Mozilla Developer Network (MDN) - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

Happy coding! 🚀
