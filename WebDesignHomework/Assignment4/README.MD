# Assignment 4 - README

## How Web Browsers Function
Web browsers act as interpreters between users and the internet. When a user enters a URL, the browser sends an HTTP or HTTPS request to the corresponding web server. The server then responds by sending back the requested HTML, CSS, and JavaScript files. The browser parses these files, constructs the DOM (Document Object Model), applies CSS for styling, executes JavaScript for interactivity, and renders the final visual representation on the screen. Additionally, modern browsers optimize performance through caching, preloading, and executing scripts asynchronously.

## What is the DOM (Document Object Model), and How Does It Power Web Pages?
The Document Object Model (DOM) is a tree-like representation of the structure and content of an HTML document. When a browser loads a web page, it creates a DOM from the HTML, where each element (such as headings, paragraphs, and images) is treated as a node. JavaScript interacts with the DOM to dynamically modify content, styles, and behaviors, making web pages interactive. Changes to the DOM update the visual representation of a webpage in real time.

## The Purpose of the index.html Page and Its Placement
The `index.html` file serves as the default entry point for a website. When a user accesses a directory on a web server without specifying a file (e.g., `www.example.com/`), the server automatically looks for `index.html` to load the homepage. It should always be placed in the root directory of a project or website folder to ensure proper accessibility and functionality.

