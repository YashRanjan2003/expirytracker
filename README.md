# Product Expiry Tracker

## Overview

Product Expiry Tracker is a web-based application that helps users keep track of product expiration dates. It uses the device's camera to capture images of product labels, extracts expiry dates using Optical Character Recognition (OCR), and allows users to manage their product inventory efficiently.

![Product Expiry Tracker Screenshot](https://i.postimg.cc/XvQvHmjj/Whats-App-Image-2024-07-08-at-22-52-54-e0a3d592.jpg)

## Features

- **Image Capture**: Use your device's camera to take square photos of product labels.
- **Automatic Date Extraction**: Utilizes Tesseract.js for OCR to detect and extract expiry dates from images.
- **Manual Date Entry**: Allows manual entry or adjustment of expiry dates.
- **Product Management**: Add, view, and delete products in your inventory.
- **Local Storage**: Saves product data locally in the browser for privacy and offline access.
- **Responsive Design**: Works on both desktop and mobile devices.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [Tesseract.js](https://tesseract.projectnaptha.com/) for OCR
- Local Storage API for data persistence

## Setup and Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/product-expiry-tracker.git
   ```

2. Navigate to the project directory:
   ```
   cd product-expiry-tracker
   ```

3. Open `index.html` in a modern web browser.

Note: For the best experience, use this application on a device with a camera and run it on a web server to avoid potential issues with camera access.

## Usage

1. **Capture Product Image**:
   - Click the "Capture Image" button.
   - Allow camera access if prompted.
   - Position the product label within the square frame and capture the image.

2. **Enter Product Details**:
   - The app will attempt to detect the expiry date automatically.
   - If detected, the date will be filled in the "Expiry Date" field.
   - Enter the product name manually.

3. **Save Product**:
   - Click "Save Product" to add the item to your inventory.

4. **View and Manage Products**:
   - Scroll down to see your saved products.
   - Each product card shows the name, expiry date, and days until expiry.
   - Use the "Delete" button to remove products from your inventory.

## Contributing

Contributions to improve Product Expiry Tracker are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- [Tesseract.js](https://tesseract.projectnaptha.com/) for providing OCR capabilities.
- All contributors who have helped to improve this project.

## Contact

Yash

Project Link: [https://github.com/YashRanjan2003/product-expiry-tracker](https://github.com/YashRanjan2003/product-expiry-tracker)
