# Markdown to HTML Renderer

This is a simple single-page web application designed to render Markdown content from an `input.md` file into HTML using Tailwind CSS for styling and `marked.js` for Markdown parsing.

## Features

*   **Markdown Rendering**: Converts `input.md` into beautifully formatted HTML.
*   **Responsive Design**: Utilizes Tailwind CSS for a mobile-first, responsive layout.
*   **Single-File Application**: All logic and presentation are contained within `index.html`.

## Getting Started

To run this application, ensure you have the following files in the same directory:

*   `index.html`: The main application file.
*   `input.md`: The Markdown file containing the content you wish to render.

Simply open `index.html` in your web browser. The script will automatically fetch `input.md`, parse it, and display its content.

## Technologies Used

*   [**Tailwind CSS**](https://tailwindcss.com/): A utility-first CSS framework for rapidly building custom designs. (CDN version used)
*   [**marked.js**](https://marked.js.org/): A full-featured Markdown parser and compiler, written in JavaScript. (CDN version used)

## File Structure

```
.
├── index.html
└── input.md
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.