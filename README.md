🔒 Secure File/Text Storage


A web application for storing and retrieving text content and files with PIN-based security.

Features

Text Storage: Store text with preview, download as file, and copy to clipboard

File Storage: Upload files with smart preview (images, PDFs, documents)

PIN Security: Unique PIN protection for each item

Modern UI: Gradient design with smooth animations

Quick Start

Setup

bashgit clone https://github.com/yourusername/secure-file-storage.git

cd secure-file-storage

Configure Backend

Run your API server on http://localhost:8081

Or update API_BASE in the HTML file


Open http://localhost:8080

Usage

Store Content

Go to "Storage" tab

Enter title and unique PIN

Add text content OR upload file

Click "Store Item"

Access Content

Go to "Access" tab

Enter your PIN

Click "Find My Items"

Select item to preview/download

API Endpoints

javascriptPOST /api/store-text    // Store text content

POST /api/store-file    // Store file uploads  

POST /api/get-item      // Retrieve items by ID + PIN

Browser Support

Chrome 70+, Firefox 65+, Safari 12+, Edge 79+

Requires: ES6, Fetch API, File API, Blob API

License

MIT License - see LICENSE file.

⭐ Star this repo if you find it useful!
