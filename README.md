# QRIS Static to Dynamic Converter

This web-based tool allows users to convert static QRIS (Quick Response Code Indonesian Standard) codes into dynamic ones. It operates entirely offline in the user's browser, ensuring the security and privacy of QRIS data.

## Features

- Convert static QRIS codes to dynamic ones
- Upload QRIS static images
- Set custom amounts for dynamic QRIS
- Add optional service fees (fixed amount or percentage)
- Display merchant information from the QRIS code
- Generate QR code for the dynamic QRIS

## How It Works

1. Upload a static QRIS image
2. The tool reads the QRIS data and displays merchant information
3. Enter the desired amount and any service fees
4. The tool generates a new dynamic QRIS code
5. A QR code is displayed for the dynamic QRIS

## Technologies Used

- HTML5
- CSS
- JavaScript (ES6+)
- jsQR (for reading QR codes)
- qrcode-generator (for generating QR codes)

## Setup

1. Clone this repository
2. Open `index.html` in a modern web browser
3. No server setup is required as this is a client-side application

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
