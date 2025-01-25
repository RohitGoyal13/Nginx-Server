# Simple Nginx-Style Server using Node.js

This project is a lightweight web server built using **Node.js**, inspired by the simplicity and efficiency of **Nginx**. It is designed to handle specific MIME types such as HTML, CSS, JavaScript, PNG, and binary files.

## Features

- **Dynamic Content Delivery**: Serves HTML, CSS, and JavaScript files for building interactive web pages.
- **Static File Handling**: Efficiently serves PNG and other binary file types.
- **Customizable MIME Types**: Easily extendable to support more file types as needed.

## Why I Built This

The purpose of this project was to understand the inner workings of web servers and build a minimal yet functional solution. This serves as both a practical tool for static web hosting and a learning experience for better understanding server architecture.

## How to Run

To get started with this server, follow the steps below:

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
Navigate to the project directory:

bash
Copy
Edit
cd <project-directory>
Install dependencies:

bash
Copy
Edit
npm install
Start the server:

bash
Copy
Edit
node server.js
This will launch the server on the default port, which can be customized in the server file.

MIME Types Supported
The server supports the following MIME types by default:

HTML: text/html
CSS: text/css
JavaScript: application/javascript
PNG: image/png
Binary Files: application/octet-stream
Folder Structure
Make sure to place your files in the public directory, or adjust the directory path in the code if needed. A typical project structure would look like this:

arduino
Copy
Edit
public/
├── index.html
├── styles.css
├── script.js
├── images/
│   └── example.png
Future Plans
Support for additional MIME types: More file types will be supported in future versions.
Caching: Implement caching strategies to improve server performance.
HTTPS Support: Integrate SSL for secure file delivery.
Improved Error Handling: Add better error messages and logging for debugging.
Contributions
Feel free to fork this project and submit pull requests if you have ideas to improve it. Contributions are welcome!

License
This project is licensed under the MIT License. You are free to use, modify, and distribute the code as per the terms of the license.

vbnet
Copy
Edit

This version has clean formatting with proper headings, bullet points, and sections that make it easy to read and copy. Let me know if you'd like further adjustments!







