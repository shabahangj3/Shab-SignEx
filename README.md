# README — Shab SignEx

## What the project does

Shab SignEx is a Windows desktop application designed to extract handwritten signatures from scanned documents, images, and PDF files. Using OpenCV-based image processing techniques, the application automatically isolates signatures from backgrounds, removes unwanted artifacts, and exports clean signature images for further use.

The software provides both automatic and manual tools to improve extraction accuracy, making it suitable for office, archival, administrative, and document-processing workflows.

---

## Key Features Include

* Signature extraction from images and PDF documents
* Multiple extraction strategies for different document types
* Automatic contour-based signature detection
* Morphological processing and text removal options
* Adjustable threshold, contrast, and blur parameters
* Region selection for targeted extraction
* Manual cleanup using an integrated eraser tool
* Real-time preview of original and processed images
* Support for transparent background output
* Export to PNG, JPG, and PDF formats
* Multi-signature navigation and processing
* Automatic update checking through GitHub releases
* Embedded resources with no external asset dependencies

---

## Why the Project Is Useful

Extracting signatures manually from scanned documents can be time-consuming and inconsistent. Shab SignEx simplifies this process by providing automated extraction tools while still allowing users to fine-tune results when necessary.

The application is useful for:

* Administrative document processing
* Digital archiving
* Contract management
* Legal and business documentation
* Signature dataset preparation
* General image cleanup and signature isolation

---

## How Users Can Get Started with the Project

### Requirements

* .NET 8.0 Runtime
* Windows operating system (x64)

### Installation

1. Download the latest release from the GitHub releases page.
2. Extract the contents of the ZIP archive.
3. Run the executable file.

### Usage

1. Launch **Shab SignEx**.
2. Click **Select File** and choose an image or PDF document.
3. Select the desired extraction strategy.
4. Adjust processing parameters such as Threshold, Blur Kernel, Contrast, and Output Width if necessary.
5. Review the extracted signature in the preview panel.
6. Use the eraser tool to remove unwanted artifacts manually.
7. Click **Save** and choose the desired output format.
8. Open the output folder directly using the **Open Output** button.

---

## Advanced Features

### Extraction Strategies

* Largest Contour (Select Region)
* Largest Contour (Auto)
* Morphological
* Signature by Complexity
* Morphological with Text Removal

### Manual Region Selection

Users can manually select a specific area of the source image to improve extraction accuracy when signatures are located within complex documents.

### Transparent Output

PNG files can be exported with transparent backgrounds, making them suitable for document templates, digital forms, and graphic design workflows.

### Signature Cleanup

The integrated eraser tool allows users to remove noise, text fragments, stamps, or unwanted pixels directly from the processed result.

### Automatic Update Checking

The application can check GitHub releases for newer versions and notify users when updates are available.

---

## Support

For help, contact the maintainer via email:

**[shabahang.j@gmail.com](mailto:shabahang.j@gmail.com)**

---

## Who Maintains and Contributes to the Project

Maintained by **shabahang.j**

Contributions are welcome via pull requests on GitHub.

---

## License

Copyright © 2026 shabahang.j

All Rights Reserved.

---

## Donate

If you find this project useful and would like to support future development, donations are appreciated:

https://nowpayments.io/donation/shabahang.j
