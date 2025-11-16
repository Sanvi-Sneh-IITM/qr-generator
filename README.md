# ADQR3 QR Code Generator

This is a simple, single-file responsive web application for generating QR codes. Just type your desired text or URL into the input field, click "Generate QR Code", and watch your QR code appear instantly.

## Features

*   **Instant Generation:** Quickly create QR codes from any text or URL.
*   **Responsive Design:** Works beautifully on desktops, tablets, and mobile phones.
*   **Minimalistic Interface:** Clean and intuitive design for ease of use.
*   **Single-File:** All code (HTML, CSS, JavaScript) is contained within one `index.html` file, making it extremely easy to deploy and share.

## Technologies Used

*   **HTML5:** For the basic structure of the web page.
*   **Tailwind CSS (CDN):** For utility-first styling and responsive design.
*   **qrcode.js (CDN):** A client-side JavaScript library for generating QR codes.

## How to Use

1.  **Open `index.html`:** Simply open the `index.html` file in any modern web browser.
2.  **Enter Text/URL:** Type the text, URL, or any data you want to encode into the QR code in the provided input field.
3.  **Generate:** Click the "Generate QR Code" button.
4.  **View QR Code:** Your QR code will appear in the white box below the button. You can right-click (or long-press on mobile) to save the image.

## Local Development (Optional)

Since this is a single-file application, no complex setup is required. You can simply open `index.html` directly in your browser.

If you wish to modify the Tailwind CSS without using the CDN, you would typically set up a local Tailwind project, but for this single-file solution, the CDN approach is used for maximum simplicity.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.