<<<<<<< HEAD
# Web Development Learning Project

This repository contains a collection of web development lessons and exercises organized by date from October 27th to November 3rd.

## Project Structure

### Daily Lessons

- **Monday (November 3rd)**
  - Basic HTML5 boilerplate setup
  - Webpack configuration (dev and prod environments)
  - Configuration files (.editorconfig, .gitignore, etc.)
  - License and documentation files

- **Friday (October 31st)**
  - CSS discussions
  - Box model examples
  - Pseudo-selectors
  - Flexbox and Grid layouts
  - Media queries and responsive design
  - Viewport configurations

- **Thursday (October 30th)**
  - HTML forms
  - CSS styling
  - Navigation implementation
  - Lottie animations integration

- **Wednesday (October 29th)**
  - VS Code introduction
  - HTML5 basics
  - Meta tags usage
  - HTML comments
  - Span vs Block elements

- **Tuesday (October 28th)**
  - Web design principles in Figma
  - HTML, CSS, and JavaScript introduction
  - DOM structure basics
  - Lottie animations

- **Saturday (November 1st)**
  - Media queries implementation
  - Responsive design practices
  - Advanced CSS styling
  - Form handling with web3forms API

## Styling

The project uses a consistent color scheme defined in CSS variables:
- Primary Color: `#6C464F`
- Secondary Color: `#9E768F`
- Auxiliary Color: `#9FA4C4`

Common styling features include:
- Responsive navigation
- Consistent typography hierarchy
- Mobile-first approach
- Cross-browser compatibility

## Development Setup

1. Install dependencies:
```bash
npm install
Technologies Used
HTML5
CSS3
JavaScript
Webpack
Lottie Animations
Web3Forms API
Browser Support
Chrome (latest)
Firefox (latest)
Safari (latest)
Edge (latest)
License
This project is licensed under the MIT License - see the LICENSE.txt file for details.

Author
Josiah Mwangi
// ...existing code...

## Resources

### Design Resources
- [Lottie Files](https://lottiefiles.com/) - For lightweight animations
- [Web3Forms](https://web3forms.com/) - For form backend functionality
- [Figma Community](https://www.figma.com/community) - Design templates and inspiration

### Development Tools
- [VS Code](https://code.visualstudio.com/) - Recommended IDE
- [Webpack Documentation](https://webpack.js.org/) - Build tool documentation
- [MDN Web Docs](https://developer.mozilla.org/) - Web development reference

### Learning Materials
- [CSS-Tricks](https://css-tricks.com/) - CSS guides and tutorials
- [JavaScript.info](https://javascript.info/) - Modern JavaScript tutorials
- [Web.dev](https://web.dev/) - Web development best practices

### Icons and Assets
- [Font Awesome](https://fontawesome.com/) - Icon library
- [Google Fonts](https://fonts.google.com/) - Typography
- [Unsplash](https://unsplash.com/) - Free high-quality images

### Testing Tools
- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)
- [Browser Stack](https://www.browserstack.com/) - Cross-browser testing
- [Can I Use](https://caniuse.com/) - Browser compatibility checks
=======
# 1stnovember2025
saturday. recap of the week
28october2025
zoom lesson 🧠 Overview

In this lesson, we learn:

How to set up an HTML document in VS Code

Basic structure and styling with CSS

Core web design principles used in Figma

How to use Lottie animations to make web pages more engaging

The role of HTML, CSS, and JavaScript in web development

🗂️ Project Structure zoom-lesson-coding/ │ ├── index.html # Main HTML file ├── style1.css # External CSS file └── (Optional) assets/ └── images/ # Add any images or Lottie animations here

🧩 Key Topics Covered 🎨 Web Design in Figma

To design effectively in Figma, consider these principles:

White Space

Color

Contrast

Scale

Typography

Visual Hierarchy

These ensure a clean, readable, and visually appealing interface.

🌀 Lottie Animations

Lottie is a tool for adding lightweight, high-quality animations to web pages.

Explore Lottie here: https://lottiefiles.com/

You can embed Lottie animations in your web design to make visuals more dynamic and interactive.

💻 HTML, CSS, and JavaScript

HTML (HyperText Markup Language): Provides the structure and content of a webpage.

CSS (Cascading Style Sheets): Adds style, layout, and visual design.

JavaScript: Brings interactivity and logic to web pages.

Together, they form the foundation of front-end web development.

🧱 Example HTML Structure

<title>Zoom Lesson Coding</title>
Welcome to the lesson
Class by Jay
🧰 Tools Used

Visual Studio Code (VS Code)

Figma

HTML5 / CSS3

LottieFiles

🚀 How to View the Project

Clone the repository:

git clone https://github.com/your-username/zoom-lesson-coding.git

# 29october2025
meta 29th october coverage
🧠 Overview

This project is part of a coding session held on Wednesday, October 28th, 2025, focusing on:

Introduction to VS Code

Basic HTML5 structure

Understanding tags and attributes

Usage of meta tags

Adding styles and images

How to use comments and inspect tools

📁 Project Structure
zoom-lesson-coding/
│
├── index.html        # Main HTML file
├── style1.css        # Linked stylesheet
└── wednesday.png     # Example image used in the lesson

💻 HTML Highlights

Declared using <!DOCTYPE html>

Language set with:

<html lang="en-us">


Meta tags included:

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">


Example of tag attributes:

<html lang="en-us">


Demonstration of inline styling:

<p style="background-color: yellow;">
  <span style="background-color: brown;">welcome to the lesson</span>
</p>

🧩 Features Covered

HTML structure and syntax

Head and body sections

Meta tags and their purposes

Image embedding with <img>

Inline CSS styling

Inspecting and commenting in VS Code

🧠 Learning Notes

Comments in HTML → Ctrl + /

Inspect website code → Right-click → Inspect

Span vs Paragraph Styling:

span applies style to text only

p applies style to the entire block

🖼️ Screenshot

Here’s an example image used in the lesson:

<img src="wednesday.png" alt="image of the viewing point of the topics" width="2000">

🧰 Tools Used


# 30october2025
meta 30th october coverage
🧾 Thursday Lesson — HTML & CSS Overview
### overview
This project is an educational HTML document created to demonstrate core web development concepts including HTML structure, form elements, and CSS selectors.
It was developed as part of a learning session held to explore how HTML works with styling and user input.

🗂️ Project Structure
project-folder/
│
├── index.html        # Main HTML lesson file
├── styles.css        # Linked stylesheet (for external styling)
└── thursday.png      # Favicon for the web page

🌟 Overview
🧠 Lesson Objective

This lesson covers:

Correct HTML structure (head, body, meta tags)

Proper placement of the CSS <link> tag

Working with forms, labels, and input types

Using Lottie animations via external libraries

Understanding CSS selectors and pseudo-classes

🏗️ Key Concepts Covered
🧩 1. Meta Tags and Performance

Demonstrates the importance of placing the <link rel="stylesheet"> near the bottom of the <body> tag to improve page load performance.

Introduces <meta> tags for viewport and SEO:

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="keywords" content="HTML,CSS overview">
<meta name="description" content="Lesson on HTML and CSS structure">

📝 2. HTML Forms

Explains how to create and structure forms for user input.

Example:

<form action="send_email.php" method="post">
  <label for="firstname">First Name:</label>
  <input type="text" name="firstname" placeholder="Your name">
  
  <label for="email">Email:</label>
  <input type="email" name="email" placeholder="example@gmail.com">
  
  <button type="submit">Submit</button>
</form>


Concepts learned:

label and input relationship

Common input types (text, number, date, email, textarea)

Dropdown menus using <select> and <option>

Button types: <input type="button"> vs <button type="submit">

🎞️ 3. Lottie Animations

Introduces the use of Lottie animations, which bring vector animations to web pages.

Library Reference:
👉 Lottie for Web (Airbnb)

Lottie files are rendered using a JavaScript library for JSON-based animations — often used as lightweight alternatives to GIFs.

🎨 4. CSS Overview

Introduces CSS syntax and types of selectors.

Basic Syntax:

selector {
  property: value;
}


Types of Selectors:

Element Selector → p { }

ID Selector → #homeImage { }

Class Selector → .homePage { }

Pseudo-class Selector → a:hover { }

Attribute Selector → a[href="https://example.com"] { }

Pseudo-classes for links:

a:link    { color: blue; }
a:visited { color: purple; }
a:hover   { color: green; }
a:active  { color: red; }

🚀 How to View the Project

Clone the repository:

git clone https://github.com/your-username/thursday-lesson.git


Open the project folder:

cd thursday-lesson


Open the file in your browser:

open index.html


(or simply double-click the index.html file)

🧰 Technologies Used

HTML5

CSS3

🧑‍💻 Author

[Josiah]
📅 Created on October 30, 2025
📧 g.lectricals@gmail.com
💻 Your GitHub Profile


# 31octpber2025
meta 31th october coverage
🌐 CSS Overview Project

This project is an educational HTML page that provides an overview of CSS fundamentals — including selectors, box model, flexbox, grid, and media queries.
It was created as part of a learning session held on October 28, to demonstrate how to apply CSS styling concepts directly within an HTML document.

🧩 Project Structure
project-folder/
│
├── index.html       # Main HTML file (lesson content)
├── styles.css       # External CSS stylesheet (linked in index.html)
└── friday.jpeg      # Favicon for the page

💡 Overview
1. Nesting in HTML & CSS

Explains how elements can be nested within each other (e.g., ul > li) and how to represent that relationship in CSS.

2. Box Model

Covers the structure of an element — margin, border, padding, and content — with examples.

3. Pseudo Selectors

Demonstrates link states such as:

a:link
a:visited
a:hover
a:active

4. Flexbox

Introduces the display: flex layout with key properties:

flex-direction

justify-content

align-items

5. CSS Grid

Shows how to use display: grid and related properties like:

column-gap

row-gap

justify-content

align-items

6. Media Queries

Explains how to make responsive designs for different screen sizes:

Mobile (up to 600px)

Tablet (601px–1024px)

Desktop (1025px and above)

7. Viewport Meta Tag

Introduces the meta tag that controls page dimensions and scaling:

<meta name="viewport" content="width=device-width, initial-scale=1.0">

🖼️ Preview

To view the project:

Clone the repository:

git clone [[https://github.com/Issa-Josiah/1octpber2025/project.git]


Open index.html in your browser.

🧠 What You’ll Learn

How CSS interacts with HTML structure.

The role of different display models (flex, grid).

How to make your page responsive with media queries.

How to use pseudo-selectors and nesting for efficient styling.

📚 Technologies Used

HTML5

CSS3

✨ Author

Open the project folder in VS Code.

Open index.html in your browser to view the page.
>>>>>>> 8f7301972f9a1b0d44d88975861751358b0f6ce2
