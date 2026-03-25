# DevanagariScan — Hindi OCR Web App

A modern, high-accuracy Hindi (Devanagari) OCR web application built using Tesseract.js.
It extracts text from images directly in the browser with advanced preprocessing and a clean user interface.

---

## Overview

DevanagariScan is a browser-based OCR tool designed specifically for Hindi text extraction.
Users can upload images or capture photos and convert them into editable Hindi text with high accuracy.

---

## Features

* Hindi-only OCR (Devanagari support)
* Fast processing using Tesseract.js
* Upload image or use camera
* Image enhancement controls:

  * Brightness
  * Contrast
  * Sharpness
* Smart preprocessing presets:

  * Document
  * Handwritten
  * Newspaper
* Detailed analytics:

  * Word count
  * Character count
  * Line count
  * Processing time
  * Confidence score
* Text-to-speech (Hindi)
* Copy, select, and download text
* Responsive and clean user interface

---

## Tech Stack

* Frontend: HTML, CSS, JavaScript
* OCR Engine: Tesseract.js
* Language Model: Hindi (hin.traineddata)
* Image Processing: Canvas API

---

## How It Works

1. Upload or capture an image containing Hindi text
2. Adjust image settings if needed
3. Click "Extract Hindi Text"
4. OCR engine processes the image
5. Extracted text is displayed along with statistics

---

## Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/your-username/devanagari-ocr.git
cd devanagari-ocr
```

### 2. Run the project

Open the HTML file in your browser:

```bash
open index.html
```

No backend is required. The application runs entirely in the browser.

---

## Hindi-Only Filtering

The project ensures that only Devanagari characters are retained using Unicode filtering:

```javascript
text.replace(/[^\u0900-\u097F\s]/g, '')
```

---

## Accuracy Tips

* Use clear and high-resolution images
* Increase contrast for better detection
* Avoid shadows and blur
* Use document preset for printed text

---

## Future Improvements

* Handwritten Hindi recognition
* Hindi to English translation
* PDF OCR support
* Cloud storage and history
* Mobile application version

---

## Contributing

Contributions are welcome. Fork the repository and submit a pull request.

---

## License

This project is open-source and available under the MIT License.

---

## Author

Utkarsh Srivastava
B.Tech CSE (AI and ML) — SMIT

---

## Support

If you find this project useful, consider giving it a star on GitHub.

https://69c2fb7391c2214868b0b68b--delightful-douhua-da6ffc.netlify.app/