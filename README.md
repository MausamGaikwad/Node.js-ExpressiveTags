# Project Title: EJS Tags Example
Overview
This project is a simple example demonstrating the usage of EJS (Embedded JavaScript) tags in a Node.js web application using the Express framework. EJS allows for dynamic content generation and rendering on the server side.

Project Structure
index.js: Main server file where Express is configured and the main route is defined.
views/index.ejs: EJS template file for rendering HTML content with dynamic data.
views/footer.ejs: EJS template file for rendering the footer section.
README.md: Project documentation file.
Getting Started
Clone the repository: ``git clone [https://github.com/MausamGaikwad/Node.js-ExpressiveTags.git](https://github.com/MausamGaikwad/Node.js-ExpressiveTags.git)``
Install dependencies: npm install
Run the application: npm start
Features
Dynamic Content Rendering: The application dynamically renders a webpage with data such as title, current seconds, a list of items, and HTML content.

Conditional Rendering: The list of items is conditionally displayed based on whether the current seconds are even or odd.

HTML Content Rendering: Demonstrates the use of <%- %> tag to render HTML content.

Footer Inclusion: The project includes a common footer using <%- include("footer.ejs") %>.

## Usage
Visit http://localhost:3000 in your web browser to view the rendered page.
License
This project is licensed under the MIT License.

## Author

Mausam Gaikwad

## Acknowledgments
- This project was created as an educational example for using EJS tags in a Node.js web application.
- The project structure and code are kept simple for learning purposes.

Feel free to fork, modify, and use this project as a starting point for your own Node.js and EJS projects. If you encounter any issues or have suggestions for improvement, please create an issue or submit a pull request. Happy coding!
