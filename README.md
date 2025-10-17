# Markdown Viewer

This is a simple, single-page web application designed to render Markdown content (`input.md`) into HTML using the `marked.js` library, styled with Tailwind CSS.

## Features

*   **Dynamic Markdown Rendering:** Automatically fetches and converts `input.md` to HTML.
*   **Responsive Design:** Built with Tailwind CSS for a mobile-first and responsive layout.
*   **Lightweight:** A single HTML file with CDN links for dependencies.

## Setup and Usage

To view this application, simply open the `index.html` file in your web browser.

Make sure the `input.md` file is located in the same directory as `index.html`. The application will automatically fetch and display its content.

## Project Structure

*   `index.html`: The main application file, containing all HTML, CSS (via Tailwind CDN), and JavaScript (for `marked.js`).
*   `input.md`: The Markdown file whose content will be rendered by `index.html`.
*   `README.md`: This file.
*   `LICENSE`: The MIT License for this project.

## Technologies Used

*   **HTML5:** For the page structure.
*   **Tailwind CSS:** For styling and responsive design.
*   **Marked.js:** A JavaScript Markdown parser and compiler.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.
