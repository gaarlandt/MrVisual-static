# How to Build a Simple Static Website

## Overview

This document provides a guide to creating a simple, multi-page static website. This type of website is fast, secure, and easy to deploy.

## Technology Stack

The website is built using a classic and robust combination of web technologies:

*   **HTML:** The core structure of the website is built with HTML. You'll create multiple `.html` files for the different pages of your site (e.g., `index.html`, `about.html`, `contact.html`).
*   **CSS:** The styling is handled by a stylesheet (e.g., `style.css`). This provides a consistent look and feel across all your pages.
*   **JavaScript:** You can use a JavaScript file (e.g., `script.js`) for interactive elements and dynamic functionality.

## File Structure

A clear and organized file structure is important for maintainability. Here is a recommended structure:

```
/
├── index.html
├── about.html
├── contact.html
├── style.css
├── script.js
└── images/
    ├── image1.jpg
    └── image2.png
```

*   **HTML Files:** Place your HTML files in the root directory for easy access. `index.html` is the conventional name for the homepage.
*   **`style.css`:** Keep your main stylesheet in the root directory. As your project grows, you might consider a `css/` or `styles/` directory.
*   **`script.js`:** Your main JavaScript file can also live in the root directory. For larger projects, a `js/` or `scripts/` directory is a good practice.
*   **`images/`:** Create a dedicated directory to store all your images.

## Getting Started

1.  **Create the HTML files:** Start by creating `index.html`. You can then create other pages as needed.
2.  **Link your CSS and JavaScript:** In each HTML file, link to your `style.css` file in the `<head>` section and your `script.js` file just before the closing `</body>` tag.
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <title>My Website</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <!-- Your content here -->
        <script src="script.js"></script>
    </body>
    </html>
    ```
3.  **Add your content:** Build out the content for each page using HTML.
4.  **Style your site:** Use CSS in `style.css` to design the look of your website.
5.  **Add interactivity:** Use JavaScript in `script.js` to add any dynamic features.

## Conclusion

This simple structure is a great starting point for many types of websites, such as portfolios, brochures, or personal sites. Its simplicity is its strength, making it fast, easy to deploy, and straightforward to update.