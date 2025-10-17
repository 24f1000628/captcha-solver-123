# Captcha Solver Application

This project provides a simple, single-file HTML application for solving captchas, designed with responsiveness using Tailwind CSS. It can load captcha images from a URL parameter or default to a local sample image.

## Features

*   **Responsive Design:** Built with Tailwind CSS for a modern, mobile-friendly interface.
*   **Dynamic Image Loading:** Loads captcha images from a `url` query parameter (e.g., `index.html?url=https://example.com/captcha.png`).
*   **Default Image:** If no `url` parameter is provided, it defaults to `sample.png`.
*   **Client-side Validation:** Includes a basic client-side validation logic for the default `sample.png` captcha.

## How to Run

1.  **Save the files:** Save `index.html`, `README.md`, and `LICENSE` in the same directory. Ensure `sample.png` is also in this directory.
2.  **Open `index.html`:** Simply open `index.html` in your web browser.

## Usage

*   **Default Mode:** To use the application with the default `sample.png` image, just open `index.html`.
*   **Custom Captcha URL:** To load a captcha image from an external URL, append the `url` query parameter to your `index.html` file in the browser's address bar:
    ```
    index.html?url=https://your-image-server.com/path/to/your/captcha.png
    ```
    Replace `https://your-image-server.com/path/to/your/captcha.png` with the actual URL of your captcha image.

**Note:** The current version includes a hardcoded solution for the `sample.png` captcha ("ADCRB") for demonstration purposes. For real-world use with dynamic images, this would typically involve a server-side component to validate captcha responses.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.