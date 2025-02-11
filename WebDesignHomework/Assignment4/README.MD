# Assignment 4 - README

## How Web Browsers Function
Web browsers act as interpreters between users and the internet. When a user enters a URL, the browser sends an HTTP or HTTPS request to the corresponding web server. The server then responds by sending back the requested HTML, CSS, and JavaScript files. The browser parses these files, constructs the DOM (Document Object Model), applies CSS for styling, executes JavaScript for interactivity, and renders the final visual representation on the screen. Additionally, modern browsers optimize performance through caching, preloading, and executing scripts asynchronously.

## What is the DOM (Document Object Model), and How Does It Power Web Pages?
The Document Object Model (DOM) is a tree-like representation of the structure and content of an HTML document. When a browser loads a web page, it creates a DOM from the HTML, where each element (such as headings, paragraphs, and images) is treated as a node. JavaScript interacts with the DOM to dynamically modify content, styles, and behaviors, making web pages interactive. Changes to the DOM update the visual representation of a webpage in real time.

## The Purpose of the index.html Page and Its Placement
The `index.html` file serves as the default entry point for a website. When a user accesses a directory on a web server without specifying a file (e.g., `www.example.com/`), the server automatically looks for `index.html` to load the homepage. It should always be placed in the root directory of a project or website folder to ensure proper accessibility and functionality.

## Review: Top Naming Practices for Clean and Organized Code
1. **Use Descriptive and Meaningful Names** – Variable, function, and file names should clearly describe their purpose.
2. **Follow Consistent Case Conventions** – Use camelCase for JavaScript variables and functions, PascalCase for classes, and kebab-case or snake_case for file names.
3. **Avoid Abbreviations and Acronyms** – Full words make the code easier to understand (e.g., `calculateTotal` instead of `calcTot`).
4. **Use Prefixes and Suffixes Where Necessary** – For example, boolean variables can start with `is` or `has` (e.g., `isVisible`, `hasError`).
5. **Organize and Group Related Files** – Use logical directory structures and meaningful folder names.
6. **Keep Function and Variable Names Short but Clear** – Avoid unnecessary words but ensure clarity (e.g., `getUserData` instead of `getDataOfUser`).

### Source:
- McConnell, Steve. *Code Complete: A Practical Handbook of Software Construction.* Microsoft Press, 2004.
