# Simple Nginx-Style Server using Node.js

This is a lightweight server built using **Node.js**, inspired by the simplicity and efficiency of **Nginx**. It serves specific MIME types such as HTML, CSS, JavaScript, PNG, and binary files.

## Features

- **Dynamic Content Delivery**: Serves HTML, CSS, and JavaScript files for building interactive web pages.
- **Static File Handling**: Efficiently serves PNG and other binary file types.
- **Customizable MIME Types**: Easily extendable to support additional file types.

## Why I Built This

The goal of this project was to understand the basics of web servers and create a minimalistic yet functional solution for static file hosting. This is both a learning experience and a practical tool for serving web content.

## How to Run

To run the server, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   
2. **Navigate to the project directory**:
   ```bash
   cd <project-directory>

3. **Install the necessary dependencies**:
   ```bash
   npm install
   
4. **Start the server:**
   ```bash
   node server.js
  This will start the server and listen on the default port (can be configured in the server file).

## MIME Types Supported

The server supports the following MIME types:

- **HTML**: `text/html`
- **CSS**: `text/css`
- **JavaScript**: `application/javascript`
- **PNG**: `image/png`
- **Binary Files**: `application/octet-stream`

## Folder Structure

Make sure to place your files in a `public` directory (or modify the server code accordingly). An example structure:


## Future Enhancements

- **Additional MIME types**: Support for more file types will be added.
- **Caching**: Implement caching mechanisms for better performance.
- **HTTPS**: Add SSL support for secure file delivery.
- **Error Handling**: Improve error handling and logging.

## Contributions

Contributions are welcome! If you have ideas for improvements, feel free to fork the repository and submit a pull request.

